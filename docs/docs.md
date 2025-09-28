
# DOCUMENTACION

## reglas para creacion de templates, plantillas forzadas
Los steps deben ocupar una linea por step, siempre, esto permite buena lectura de los mismos
Tiene ciertos selectores y campos de texto base que deben usar tilde tal cual, cambiarlos podria dejar de funcionar las plantillas

## maps.json 
contiene los selector mappings, debe estar copiado en todas las plantillas de este repositorio


## label
Nombre de la plantilla


## Readme contiene las plantillas pendientes a desarrollo

## AdultoSano.json y las plantillas de acciones especificas indican llenado apropiado de templates

## Tipo de Atención
Intramural
Extramural

## Lugar de Atención
### Establecimiento de Salud siempre va forzado con Intramural
Establecimiento de Salud
Domicilio
Comunidad
Otros

## Texto Medicamentos receta

IBUPROFENO - SOLIDO ORAL - 400
PARACETAMOL - SOLIDO ORAL - 500
DICLOFENACO - LIQUIDO PARENTERAL - 25
LORATADINA - SOLIDO ORAL - 10
LORATADINA - LIQUIDO ORAL - 5/5
HIERRO, MULTIVITAMINAS Y MINERALES: HIERRO - ZINC - VITAMINA A - ACIDO FOLICO - ACIDO ASCORBICO - SOLIDO ORAL (POLVO)
SALES DE HIERRO + ACIDO FOLICO - SOLIDO ORAL - 60
RETINOL (VITAMINA A) - SOLIDO ORAL (CAPSULA BLANDA) - 50000 UI
AMOXICILINA + ACIDO CLAVULANICO - SOLIDO ORAL - 500 + 125
ACIDO FOLICO - SOLIDO ORAL - 5
ACIDO FOLICO - SOLIDO ORAL - 1
CALCIO CARBONATO - SOLIDO ORAL - 500
ACIDO ACETIL SALICILICO - SOLIDO ORAL - 100
ACIDO ACETIL SALICILICO - SOLIDO ORAL - 500
NITROFURANTOINA - SOLIDO ORAL - 100
FOSFOMICINA - SOLIDO ORAL - 500 mg
HIERRO POLIMALTOSADO - SOLIDO ORAL - 100
ALBENDAZOL - SOLIDO ORAL - 400 mg
TINIDAZOL - SOLIDO ORAL - 1000 mg
OMEPRAZOL - SOLIDO ORAL - 20 mg
METFORMINA - SOLIDO ORAL - 500
METFORMINA - SOLIDO ORAL - 750
METFORMINA - SOLIDO ORAL - 1000
METFORMINA - SOLIDO ORAL - 850
SALES DE REHIDRATACION ORAL
KETOROLACO - LIQUIDO PARENTERAL - 30
CARBAMAZEPINA - SOLIDO ORAL (LIBERACION CONTROLADA) - 400
CARBAMAZEPINA - SOLIDO ORAL - 200
RISPERIDONA - LIQUIDO ORAL
DICLOFENACO - SOLIDO ORAL - 50
AMOXICILINA + ACIDO CLAVULANICO - SOLIDO ORAL - 500 + 125
AMOXICILINA + ACIDO CLAVULANICO - SOLIDO ORAL - 875 + 125
AMOXICILINA - SOLIDO ORAL - 500 mg
AZITROMICINA - SOLIDO ORAL - 500 mg
FOSFOMICINA - SOLIDO ORAL (GRANULOS) - 3
SALBUTAMOL - LIQUIDO PARA INHALACION - 0.1
SALBUTAMOL - LIQUIDO PARA NEBULIZACION / LIQUIDO PARA INHALACION - 5
BECLOMETASONA - LIQUIDO PARA INHALACION - 50
BECLOMETASONA - LIQUIDO PARA INHALACION - 250
PRATROPIO BROMURO - LIQUIDO PARA NEBULIZACION / LIQUIDO PARA INHALACION - 0.25
ACETILCISTEINA - LIQUIDO PARA INHALACION - 100
LOPERAMIDA - SOLIDO ORAL - 2
GLICLAZIDA - SOLIDO ORAL (LIBERACION PROLONGADA) - 30
GLICLAZIDA - SOLIDO ORAL (LIBERACION PROLONGADA) - 60
INSULINA HUMANA (ACCION RAPIDA) - LIQUIDO PARENTERAL - 100
FERROSO SULFATO - SOLIDO ORAL - 50
FERROSO SULFATO - LIQUIDO ORAL - 25

LOSARTAN - SOLIDO ORAL - 100
LOSARTAN - SOLIDO ORAL - 50

FUROSEMIDA - SOLIDO ORAL - 40 mg
ESPIRONOLACTONA - SOLIDO ORAL - 25
ESPIRONOLACTONA - SOLIDO ORAL - 100
AMLODIPINA - SOLIDO ORAL - 5
AMLODIPINA - SOLIDO ORAL - 10
NIFEDIPINA - SOLIDO ORAL - 10
CLORTALIDONA - SOLIDO ORAL - 25
CLORTALIDONA - SOLIDO ORAL - 50
ENALAPRIL - SOLIDO ORAL - 5
ENALAPRIL - SOLIDO ORAL - 10
ENALAPRIL - SOLIDO ORAL - 20
CARVEDILOL - SOLIDO ORAL - 6.25
CARVEDILOL - SOLIDO ORAL - 12.5
CARVEDILOL - SOLIDO ORAL - 25
ATENOLOL - SOLIDO ORAL - 50
ATENOLOL - SOLIDO ORAL - 100
CLOTRIMAZOL - SEMISOLIDO VAGINAL - 1
CLOTRIMAZOL - SEMISOLIDO VAGINAL - 2
CLOTRIMAZOL - SOLIDO VAGINAL - 200
CLOTRIMAZOL - SOLIDO VAGINAL - 500
MISOPROSTOL - SOLIDO ORAL - 200
LEVONORGESTREL + ETINILESTRADIOL - SOLIDO ORAL - 150 + 30
LEVONORGESTREL - SOLIDO ORAL - 0.75
LEVONORGESTREL - SOLIDO ORAL - 1.5
LEVONORGESTREL - SOLIDO ORAL - 0.03
LEVONORGESTREL - SOLIDO PARENTERAL (IMPLANTE SUBDERMICO) - 150
ERITROMICINA - SOLIDO ORAL - 500
ERITROMICINA - SOLIDO ORAL - 250

## Medida receta
Miligramo
Mililitro
Unidades
Gramo
Unidades Internacionales

## Frecuencia receta
Cada 4 Horas
Cada 6 Horas
Cada 8 Horas
Cada 12 Horas
Cada 24 Horas
En Este Momento
Por Razones Necesarias
Otra
### en caso de usar Otra se debe llenar el campo de texto receta frecuencia otra con valores de texto personalizadas ej (pasando un dia, cada 48 horas, cada semana, etc)

## Via Administracion
ORAL
INHALATORIA
PARENTERAL
INTRATRAQUEAL
RECTAL
VAGINAL
INTRAUTERINA
INTRAVESICAL
OCULAR
ORAL/VAGINAL
OTRO
PARENTERAL (INTRAVENOSA)
PARENTERAL (INTRAMUSCULAR)
PARENTERAL (INTRAVENOSO/INTRAMUSCULAR)
PARENTERAL (INTRAVENOSO/INTRAMUSCULAR/SUBCUTÁNEO)
PARENTERAL (SUBCUTÁNEA)
TÓPICO


## Receta estado paciente (se escoge en base al CIE 10)
Agudo
Crónico

## Receta especialidad
Medicina General
Odontología

## CIE 10 (algunos ejemplos)

J00X
M545

Z000
Z003
Z713
Z300
Z013


Z301
Z308

Z304
Z305

Z316


## CIE 10 forzados


### Adolecente 10-19 años
Z003
Z713
Z300
### Niño
Z001

## Diagnostico Especial

Menores a 5 años: clic en panel diagnostico aparece pestaña, se debe marcar control_rutina_si y control_rutina_guardar, no se coloca cie 10 Z001, sistema ya rellena automaticamente, condicion de diagnostico no se llena, cronologia se llena como subsecuente, primera solo es si es Recien nacido luego  se confirma diagnostico

5-9 años: usar Z002, se debe rellenar normal.

### Control Embarazo

Preconcepcional, seleccionar mappings comunes, adulto sano: alimentacion, higiene, actividad fisica.

Para Gestante, seleccionar mappings de  3 recomendaciones de gestante: alimentacion, higiene, educacion lactancia

Para Mujer postparto o Madre en Periodo de Lactancia, seleccionar mappings de 3 recomendaciones de madre en periodo de lactancia: lactancia exclusiva, higiene, actividad 30 min

#### Cie 10 para primer control embarazo

Z720 
Z721 
Z722 
Z723 
Z724 
Z725 


### Cie 10 Gestante siempre
Z348 
Z713
### Cie 10 Madre periodo lactancia
Z391

#### Cie 10 Gestante solo en periodos que se envia examenes
Z113 
Z118
Z130 
Z131 
Z132 

Z360
Z361
Z362
Z363
Z364
Z368