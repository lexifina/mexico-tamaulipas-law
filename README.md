# Tamaulipas: law history in git

The law of the State of Tamaulipas (Estado Libre y Soberano de Tamaulipas, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-tam/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

157 ordenamientos with 2260 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE TAMAULIPAS | 254 | as first published, then each reform: 8 February 1921 to 13 October 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE TAMAULIPAS | 72 | as first published, then each reform: 1 February 1987 to 31 March 2026 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES DEL ESTADO DE TAMAULIPAS | 36 | as first published, then each reform: 24 October 1961 to 19 December 2017 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE TAMAULIPAS | 27 | as first published, then each reform: 1 January 1992 to 1 January 2026 |
| `codigo-municipal/` | CODIGO MUNICIPAL PARA EL ESTADO DE TAMAULIPAS | 154 | as first published, then each reform: 4 February 1984 to 2 October 2026 |
| `codigo-para-el-desarrollo-sustentable/` | CODIGO PARA EL DESARROLLO SUSTENTABLE DEL ESTADO DE TAMAULIPAS | 27 | as first published, then each reform: 3 September 2008 to 29 October 2026 |
| `codigo-para-la-prevencion-de-conflictos-de-interes-de-las-y/` | CODIGO PARA LA PREVENCION DE CONFLICTOS DE INTERES DE LAS Y LOS SERVIDORES PUBLICOS DE LA SECRETARIA DE FINANZAS DEL GOBIERNO DEL ESTADO DE TAMAULIPAS | 1 | as first published: 9 August 2025 |
| `codigo-para-la-prevencion-y-conflictos-de-interes-de-las-y-l/` | CODIGO PARA LA PREVENCION Y CONFLICTOS DE INTERES DE LAS Y LOS SERVIDORES PUBLICOS DEL COLEGIO DE EDUCACION PROFESIONAL TECNICA DEL ESTADO DE TAMAULIPAS | 1 | as first published: 14 August 2019 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO DE TAMAULIPAS | 186 | as first published, then each reform: 23 December 1986 to 29 October 2026 |
| `ley-constitutiva-de-la-universidad-autonoma-de-tamaulipas-an/` | LEY CONSTITUTIVA DE LA UNIVERSIDAD AUTONOMA DE TAMAULIPAS -ANTES LEY CONSTITUTIVA DE LA UNIVERSIDAD DE TAMAULIPAS- | 7 | as first published, then each reform: 11 February 1956 to 16 February 2023 |
| `ley-de-adopciones/` | LEY DE ADOPCIONES PARA EL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 9 May 2017 to 7 June 2023 |
| `ley-de-adquisiciones-para-la-administracion-publica/` | LEY DE ADQUISICIONES PARA LA ADMINISTRACION PUBLICA DEL ESTADO DE TAMAULIPAS Y SUS MUNICIPIOS | 10 | as first published, then each reform: 30 December 2010 to 26 June 2026 |
| `ley-de-aguas/` | LEY DE AGUAS DEL ESTADO DE TAMAULIPAS | 41 | as first published, then each reform: 16 February 2006 to 6 October 2026 |
| `ley-de-amnistia/` | LEY DE AMNISTIA DEL ESTADO DE TAMAULIPAS | 1 | as first published: 30 September 2022 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 22 December 2024 to 19 August 2026 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE TAMAULIPAS | 13 | as first published, then each reform: 6 February 2019 to 18 March 2026 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 2 December 2017 to 13 February 2026 |
| `ley-de-atencion-a-victimas/` | LEY DE ATENCION A VICTIMAS PARA EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 17 December 2024 to 10 March 2026 |
| `ley-de-bibliotecas-publicas/` | LEY DE BIBLIOTECAS PUBLICAS DEL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 27 May 2015 to 26 August 2026 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO Y MUNICIPIOS DE TAMAULIPAS | 12 | as first published, then each reform: 11 April 2005 to 13 February 2026 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 21 June 2017 to 16 October 2024 |
| `ley-de-caminos/` | LEY DE CAMINOS DEL ESTADO DE TAMAULIPAS | 9 | as first published, then each reform: 19 November 2008 to 13 February 2026 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE TAMAULIPAS | 12 | as first published, then each reform: 31 October 2001 to 26 June 2026 |
| `ley-de-centros-de-atencion-infantil/` | LEY DE CENTROS DE ATENCION INFANTIL DEL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 26 November 2014 to 9 September 2021 |
| `ley-de-conciliacion-y-arbitraje-medico/` | LEY DE CONCILIACION Y ARBITRAJE MEDICO PARA EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 26 December 2010 to 13 February 2026 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE TAMAULIPAS | 26 | as first published, then each reform: 1 January 2008 to 25 February 2026 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE PARA EL ESTADO DE TAMAULIPAS | 18 | as first published, then each reform: 3 July 2014 to 26 August 2026 |
| `ley-de-derechos-del-contribuyente/` | LEY DE DERECHOS DEL CONTRIBUYENTE DEL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 1 January 2008 to 1 January 2012 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 6 June 2007 to 10 September 2021 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE TAMAULIPAS | 10 | as first published, then each reform: 5 July 2012 to 6 October 2026 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL PARA EL ESTADO DE TAMAULIPAS | 13 | as first published, then each reform: 25 November 2004 to 26 August 2026 |
| `ley-de-deuda-publica-estatal-y-municipal-de-tamaulipas/` | LEY DE DEUDA PUBLICA ESTATAL Y MUNICIPAL DE TAMAULIPAS | 14 | as first published, then each reform: 31 December 1995 to 13 February 2026 |
| `ley-de-educacion/` | LEY DE EDUCACION PARA EL ESTADO DE TAMAULIPAS | 21 | as first published, then each reform: 24 August 2023 to 29 October 2026 |
| `ley-de-ejecucion-de-sanciones-privativas-y-restrictivas-de-l/` | LEY DE EJECUCION DE SANCIONES PRIVATIVAS Y RESTRICTIVAS DE LA LIBERTAD DEL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 28 December 2007 to 4 April 2014 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE TAMAULIPAS | 9 | as first published, then each reform: 29 October 2012 to 2 October 2025 |
| `ley-de-escalafon-inamovilidad-seguro-y-recompensa-del-maestr/` | LEY DE ESCALAFON, INAMOVILIDAD, SEGURO Y RECOMPENSA DEL MAESTRO, QUE REFORMA Y ADICIONA LA LEY DE EDUCACION PUBLICA DEL ESTADO | 1 | as first published: 16 August 1935 |
| `ley-de-expropiacion-ocupacion-temporal-o-limitacion-de-domin/` | LEY DE EXPROPIACION, OCUPACION TEMPORAL O LIMITACION DE DOMINIO PARA EL ESTADO DE TAMAULIPAS | 7 | as first published, then each reform: 26 April 1992 to 6 July 2023 |
| `ley-de-firma-electronica-avanzada/` | LEY DE FIRMA ELECTRONICA AVANZADA PARA EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 16 November 2013 to 23 May 2025 |
| `ley-de-fiscalizacion-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION Y RENDICION DE CUENTAS DEL ESTADO DE TAMAULIPAS | 8 | as first published, then each reform: 3 June 2017 to 13 February 2026 |
| `ley-de-fomento-a-la-cultura/` | LEY DE FOMENTO A LA CULTURA PARA EL ESTADO DE TAMAULIPAS | 7 | as first published, then each reform: 2 September 2011 to 26 August 2026 |
| `ley-de-fomento-a-la-investigacion-cientifica-y-tecnologica-e/` | LEY DE FOMENTO A LA INVESTIGACION CIENTIFICA Y TECNOLOGICA EN EL ESTADO DE TAMAULIPAS | 13 | as first published, then each reform: 20 August 2004 to 20 November 2025 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE TAMAULIPAS | 8 | as first published, then each reform: 3 August 2007 to 15 July 2021 |
| `ley-de-fomento-y-uso-de-la-bicicleta-en-el-estado-de-tamauli/` | LEY DE FOMENTO Y USO DE LA BICICLETA EN EL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 21 September 2016 to 31 October 2018 |
| `ley-de-fraccionamiento-de-latifundios/` | LEY DE FRACCIONAMIENTO DE LATIFUNDIOS | 2 | as first published, then each reform: 1 August 1936 to 21 April 2004 |
| `ley-de-ganaderia/` | LEY DE GANADERIA PARA EL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 8 March 2024 to 29 October 2026 |
| `ley-de-gasto-publico/` | LEY DE GASTO PUBLICO | 19 | as first published, then each reform: 1 January 2002 to 13 February 2026 |
| `ley-de-hacienda/` | LEY DE HACIENDA PARA EL ESTADO DE TAMAULIPAS | 52 | as first published, then each reform: 1 January 2008 to 19 August 2026 |
| `ley-de-informacion-geografica-y-estadistica/` | LEY DE INFORMACION GEOGRAFICA Y ESTADISTICA DEL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 14 April 1994 to 22 December 2016 |
| `ley-de-infraestructura-fisica-educativa/` | LEY DE INFRAESTRUCTURA FISICA EDUCATIVA PARA EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 8 July 2009 to 7 June 2023 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE TAMAULIPAS PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-el-mante-tamaulipas-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE EL MANTE, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 17 June 2026 |
| `ley-de-ingresos-del-municipio-de-gonzalez-tamaulipas-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE GONZALEZ, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 17 June 2026 |
| `ley-de-ingresos-del-municipio-de-jaumave-tamaulipas-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE JAUMAVE, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 17 June 2026 |
| `ley-de-ingresos-del-municipio-de-llera-tamaulipas-para-el-ej/` | LEY DE INGRESOS DEL MUNICIPIO DE LLERA, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 2 July 2026 |
| `ley-de-ingresos-del-municipio-de-mainero-tamaulipas-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE MAINERO, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 3 June 2026 |
| `ley-de-ingresos-del-municipio-de-matamoros-tamaulipas-para-e/` | LEY DE INGRESOS DEL MUNICIPIO DE MATAMOROS, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 3 June 2026 |
| `ley-de-ingresos-del-municipio-de-mendez-tamaulipas-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE MENDEZ, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 2 July 2026 |
| `ley-de-ingresos-del-municipio-de-miguel-aleman-tamaulipas-pa/` | LEY DE INGRESOS DEL MUNICIPIO DE MIGUEL ALEMAN, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 2 July 2026 |
| `ley-de-ingresos-del-municipio-de-miquihuana-tamaulipas-para/` | LEY DE INGRESOS DEL MUNICIPIO DE MIQUIHUANA, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 3 June 2026 |
| `ley-de-ingresos-del-municipio-de-rio-bravo-tamaulipas-para-e/` | LEY DE INGRESOS DEL MUNICIPIO DE RIO BRAVO, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 7 July 2026 |
| `ley-de-ingresos-del-municipio-de-san-carlos-tamaulipas-para/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN CARLOS, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 17 June 2026 |
| `ley-de-ingresos-del-municipio-de-san-fernando-tamaulipas-par/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN FERNANDO, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 3 June 2026 |
| `ley-de-ingresos-del-municipio-de-tampico-tamaulipas-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE TAMPICO, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 3 | as first published, then each reform: 1 January 2026 to 2 July 2026 |
| `ley-de-ingresos-del-municipio-de-tula-tamaulipas-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE TULA, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 3 June 2026 |
| `ley-de-ingresos-del-municipio-de-villagran-tamaulipas-para-e/` | LEY DE INGRESOS DEL MUNICIPIO DE VILLAGRAN, TAMAULIPAS, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 2 | as first published, then each reform: 1 January 2026 to 3 June 2026 |
| `ley-de-instituciones-de-asistencia-social/` | LEY DE INSTITUCIONES DE ASISTENCIA SOCIAL PARA EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 6 January 1991 to 11 June 2026 |
| `ley-de-la-comision-de-derechos-humanos/` | LEY DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE TAMAULIPAS | 16 | as first published, then each reform: 6 February 1994 to 4 June 2025 |
| `ley-de-la-defensoria-publica/` | LEY DE LA DEFENSORIA PUBLICA PARA EL ESTADO DE TAMAULIPAS | 8 | as first published, then each reform: 1 July 2013 to 25 November 2023 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores-en-el-es/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES EN EL ESTADO DE TAMAULIPAS | 26 | as first published, then each reform: 7 December 2001 to 26 August 2026 |
| `ley-de-los-derechos-de-las-personas-con-discapacidad/` | LEY DE LOS DERECHOS DE LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE TAMAULIPAS | 24 | as first published, then each reform: 28 September 2016 to 15 April 2026 |
| `ley-de-los-derechos-de-las-personas-jovenes/` | LEY DE LOS DERECHOS DE LAS PERSONAS JOVENES DEL ESTADO DE TAMAULIPAS | 7 | as first published, then each reform: 22 December 2023 to 26 August 2026 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE TAMAULIPAS | 53 | as first published, then each reform: 2 July 2015 to 29 October 2026 |
| `ley-de-mediacion/` | LEY DE MEDIACION PARA EL ESTADO DE TAMAULIPAS | 8 | as first published, then each reform: 20 October 2007 to 7 June 2023 |
| `ley-de-medios-de-impugnacion-electorales-de-tamaulipas/` | LEY DE MEDIOS DE IMPUGNACION ELECTORALES DE TAMAULIPAS | 11 | as first published, then each reform: 30 December 2008 to 30 May 2026 |
| `ley-de-movilidad/` | LEY DE MOVILIDAD DEL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 30 April 2023 to 31 March 2026 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS PARA EL ESTADO DE TAMAULIPAS | 20 | as first published, then each reform: 19 November 2003 to 13 February 2026 |
| `ley-de-participacion-ciudadana-del-estado/` | LEY DE PARTICIPACION CIUDADANA DEL ESTADO | 5 | as first published, then each reform: 7 June 2001 to 13 February 2026 |
| `ley-de-paternidad-y-maternidad-responsable/` | LEY DE PATERNIDAD Y MATERNIDAD RESPONSABLE DEL ESTADO DE TAMAULIPAS -ANTES LEY DE PATERNIDAD RESPONSABLE DEL ESTADO DE TAMAULIPAS- | 6 | as first published, then each reform: 15 January 2005 to 7 June 2023 |
| `ley-de-pesca-y-acuacultura-sustentables/` | LEY DE PESCA Y ACUACULTURA SUSTENTABLES DEL ESTADO DE TAMAULIPAS | 8 | as first published, then each reform: 2 September 2011 to 18 February 2026 |
| `ley-de-premios-estimulos-y-recompensas/` | LEY DE PREMIOS, ESTIMULOS Y RECOMPENSAS DEL ESTADO DE TAMAULIPAS | 16 | as first published, then each reform: 25 January 1988 to 14 April 2026 |
| `ley-de-prevencion-de-la-violencia-familiar/` | LEY DE PREVENCION DE LA VIOLENCIA FAMILIAR DEL ESTADO DE TAMAULIPAS | 12 | as first published, then each reform: 25 June 2008 to 27 June 2026 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO PARA EL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 6 July 2017 to 10 April 2026 |
| `ley-de-promocion-a-la-lectura-y-creacion-de-libros/` | LEY DE PROMOCION A LA LECTURA Y CREACION DE LIBROS PARA EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 28 August 2013 to 26 August 2026 |
| `ley-de-proteccion-a-los-animales/` | LEY DE PROTECCION A LOS ANIMALES PARA EL ESTADO DE TAMAULIPAS | 23 | as first published, then each reform: 17 December 2010 to 29 October 2026 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE TAMAULIPAS | 1 | as first published: 19 December 2025 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-los-suj/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE LOS SUJETOS OBLIGADOS DEL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 11 July 2025 to 31 March 2026 |
| `ley-de-proteccion-para-los-no-fumadores/` | LEY DE PROTECCION PARA LOS NO FUMADORES DEL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 7 September 2006 to 7 June 2023 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE TAMAULIPAS Y SUS MUNICIPIOS | 6 | as first published, then each reform: 10 February 2005 to 30 September 2025 |
| `ley-de-responsabilidades-administrativas/` | LEY DE RESPONSABILIDADES ADMINISTRATIVAS DEL ESTADO DE TAMAULIPAS | 9 | as first published, then each reform: 5 June 2017 to 26 June 2026 |
| `ley-de-responsabilidades-de-los-servidores-publicos/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE TAMAULIPAS | 19 | as first published, then each reform: 4 March 1984 to 26 August 2023 |
| `ley-de-salud/` | LEY DE SALUD PARA EL ESTADO DE TAMAULIPAS | 83 | as first published, then each reform: 28 November 2001 to 13 October 2026 |
| `ley-de-seguridad-escolar/` | LEY DE SEGURIDAD ESCOLAR PARA EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 26 April 2008 to 16 October 2024 |
| `ley-de-seguridad-publica/` | LEY DE SEGURIDAD PUBLICA PARA EL ESTADO DE TAMAULIPAS | 16 | as first published, then each reform: 15 April 2020 to 13 February 2026 |
| `ley-de-transito/` | LEY DE TRANSITO DEL ESTADO DE TAMAULIPAS - ANTES LEY DE TRANSITO Y TRANSPORTE - | 31 | as first published, then each reform: 30 December 1987 to 6 October 2026 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 11 July 2025 to 19 August 2026 |
| `ley-de-transporte/` | LEY DE TRANSPORTE DEL ESTADO DE TAMAULIPAS | 20 | as first published, then each reform: 13 February 2002 to 30 April 2026 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE TAMAULIPAS | 24 | as first published, then each reform: 4 July 2014 to 7 July 2026 |
| `ley-de-valuacion/` | LEY DE VALUACION DEL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 10 November 2010 to 13 July 2018 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE TAMAULIPAS | 9 | as first published, then each reform: 24 December 2013 to 26 August 2026 |
| `ley-del-colegio-de-tamaulipas/` | LEY DEL COLEGIO DE TAMAULIPAS | 4 | as first published, then each reform: 17 October 2002 to 21 August 2019 |
| `ley-del-ejercicio-profesional-en-el-estado-de-tamaulipas/` | LEY DEL EJERCICIO PROFESIONAL EN EL ESTADO DE TAMAULIPAS | 10 | as first published, then each reform: 19 October 1986 to 7 April 2022 |
| `ley-del-expediente-clinico-electronico-en-tamaulipas/` | LEY DEL EXPEDIENTE CLINICO ELECTRONICO EN TAMAULIPAS | 3 | as first published, then each reform: 20 September 2013 to 22 December 2016 |
| `ley-del-instituto-de-prevision-y-seguridad-social/` | LEY DEL INSTITUTO DE PREVISION Y SEGURIDAD SOCIAL DEL ESTADO DE TAMAULIPAS | 8 | as first published, then each reform: 1 January 2015 to 7 April 2026 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE TAMAULIPAS | 18 | as first published, then each reform: 14 February 2008 to 30 April 2026 |
| `ley-del-patrimonio-historico-y-cultural-del-estado/` | LEY DEL PATRIMONIO HISTORICO Y CULTURAL DEL ESTADO | 8 | as first published, then each reform: 27 November 1997 to 20 July 2023 |
| `ley-del-periodico-oficial/` | LEY DEL PERIODICO OFICIAL DEL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 11 May 2006 to 21 December 2023 |
| `ley-del-procedimiento-contencioso-administrativo/` | LEY DEL PROCEDIMIENTO CONTENCIOSO ADMINISTRATIVO DEL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 9 June 2017 to 13 October 2023 |
| `ley-del-registro-publico-de-la-propiedad-inmueble-y-del-come/` | LEY DEL REGISTRO PUBLICO DE LA PROPIEDAD INMUEBLE Y DEL COMERCIO | 10 | as first published, then each reform: 29 March 2008 to 28 February 2024 |
| `ley-del-sistema-de-seguridad-publica/` | LEY DEL SISTEMA DE SEGURIDAD PUBLICA DEL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 21 December 2025 to 1 July 2026 |
| `ley-del-sistema-estatal-anticorrupcion-de-tamaulipas/` | LEY DEL SISTEMA ESTATAL ANTICORRUPCION DE TAMAULIPAS | 5 | as first published, then each reform: 3 June 2017 to 13 February 2026 |
| `ley-del-trabajo-de-los-servidores-publicos/` | LEY DEL TRABAJO DE LOS SERVIDORES PUBLICOS DEL ESTADO DE TAMAULIPAS | 37 | as first published, then each reform: 7 December 2001 to 13 October 2026 |
| `ley-electoral/` | LEY ELECTORAL DEL ESTADO DE TAMAULIPAS | 15 | as first published, then each reform: 14 June 2015 to 30 May 2026 |
| `ley-en-materia-de-desaparicion-y-busqueda-de-personas/` | LEY EN MATERIA DE DESAPARICION Y BUSQUEDA DE PERSONAS DEL ESTADO DE TAMAULIPAS | 1 | as first published: 18 December 2025 |
| `ley-estatal-de-planeacion/` | LEY ESTATAL DE PLANEACION | 13 | as first published, then each reform: 20 September 1984 to 31 March 2026 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE TAMAULIPAS | 23 | as first published, then each reform: 5 May 2023 to 1 October 2026 |
| `ley-organica-de-la-fiscalia-general-de-justicia/` | LEY ORGANICA DE LA FISCALIA GENERAL DE JUSTICIA DEL ESTADO DE TAMAULIPAS | 23 | as first published, then each reform: 18 November 2019 to 25 March 2026 |
| `ley-organica-del-centro-de-conciliacion-laboral/` | LEY ORGANICA DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 2 October 2021 to 13 February 2026 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 1 October 2025 to 6 March 2026 |
| `ley-organica-del-tribunal-de-justicia-administrativa/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 3 June 2017 to 13 February 2026 |
| `ley-para-el-desarrollo-economico-competitividad-e-innovacion/` | LEY PARA EL DESARROLLO ECONOMICO, COMPETITIVIDAD E INNOVACION DEL ESTADO DE TAMAULIPAS - ANTES LEY PARA EL DESARROLLO ECONOMICO Y LA COMPETITIVIDAD DEL ESTADO DE TAMAULIPAS - | 19 | as first published, then each reform: 25 November 2005 to 30 September 2026 |
| `ley-para-el-desarrollo-familiar/` | LEY PARA EL DESARROLLO FAMILIAR DEL ESTADO DE TAMAULIPAS | 11 | as first published, then each reform: 29 December 2004 to 23 May 2026 |
| `ley-para-el-fomento-de-la-apicultura-en-el-estado-de-tamauli/` | LEY PARA EL FOMENTO DE LA APICULTURA EN EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 17 December 2004 to 10 April 2026 |
| `ley-para-el-fomento-y-desarrollo-artesanal/` | LEY PARA EL FOMENTO Y DESARROLLO ARTESANAL DEL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 8 October 2004 to 27 November 2025 |
| `ley-para-el-fomento-y-desarrollo-de-la-fruticultura-en-el-es/` | LEY PARA EL FOMENTO Y DESARROLLO DE LA FRUTICULTURA EN EL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 28 October 2004 to 22 December 2016 |
| `ley-para-el-fomento-y-el-aprovechamiento-sustentable-de-la-e/` | LEY PARA EL FOMENTO Y EL APROVECHAMIENTO SUSTENTABLE DE LA ENERGIA EN EL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 24 September 2021 to 27 June 2026 |
| `ley-para-el-reconocimiento-y-atencion-de-las-personas-lgbttt/` | LEY PARA EL RECONOCIMIENTO Y ATENCION DE LAS PERSONAS LGBTTTI+ PARA EL ESTADO DE TAMAULIPAS | 1 | as first published: 5 March 2026 |
| `ley-para-el-registro-y-acreditacion-de-los-agentes-y-profesi/` | LEY PARA EL REGISTRO Y ACREDITACION DE LOS AGENTES Y PROFESIONALES INMOBILIARIOS DEL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 15 July 2016 to 22 December 2016 |
| `ley-para-fomentar-la-donacion-altruista-de-articulos-de-prim/` | LEY PARA FOMENTAR LA DONACION ALTRUISTA DE ARTICULOS DE PRIMERA NECESIDAD DEL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 28 October 2004 to 18 August 2017 |
| `ley-para-la-administracion-de-bienes-asegurados-decomisados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS O ABANDONADOS DEL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 26 May 2015 to 15 July 2021 |
| `ley-para-la-atencion-proteccion-e-inclusion-de-las-personas/` | LEY PARA LA ATENCION, PROTECCION E INCLUSION DE LAS PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA Y TRASTORNOS DEL NEURODESARROLLO PARA EL ESTADO DE TAMAULIPAS (ANTES: LEY PARA LA ATENCION Y PROTECCION A PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA DEL ESTADO DE TAMAULIPAS) | 9 | as first published, then each reform: 27 May 2016 to 28 February 2026 |
| `ley-para-la-deteccion-oportuna-del-cancer-en-la-infancia-y-l/` | LEY PARA LA DETECCION OPORTUNA DEL CANCER EN LA INFANCIA Y LA ADOLESCENCIA EN EL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 19 November 2022 to 7 June 2023 |
| `ley-para-la-entrega-recepcion-de-los-recursos-asignados-a-lo/` | LEY PARA LA ENTREGA-RECEPCION DE LOS RECURSOS ASIGNADOS A LOS PODERES, ORGANOS Y AYUNTAMIENTOS DEL ESTADO DE TAMAULIPAS (ANTES: LEY PARA LA ENTREGA-RECEPCION DE LOS RECURSOS ASIGNADOS A LOS PODERES Y AYUNTAMIENTOS DEL ESTADO DE TAMAULIPAS) | 10 | as first published, then each reform: 7 November 2003 to 17 April 2026 |
| `ley-para-la-igualdad-de-genero-en-tamaulipas/` | LEY PARA LA IGUALDAD DE GENERO EN TAMAULIPAS | 8 | as first published, then each reform: 7 December 2018 to 27 June 2026 |
| `ley-para-la-operacion-y-funcionamiento-de-establecimientos-d/` | LEY PARA LA OPERACION Y FUNCIONAMIENTO DE ESTABLECIMIENTOS DE BEBIDAS ALCOHOLICAS PARA EL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 1 January 2025 to 1 January 2026 |
| `ley-para-la-prestacion-del-servicio-publico-de-panteones-en/` | LEY PARA LA PRESTACION DEL SERVICIO PUBLICO DE PANTEONES EN EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 21 May 2003 to 24 October 2025 |
| `ley-para-la-prevencion-de-la-violencia-en-el-entorno-escolar/` | LEY PARA LA PREVENCION DE LA VIOLENCIA EN EL ENTORNO ESCOLAR DEL ESTADO DE TAMAULIPAS | 7 | as first published, then each reform: 18 September 2013 to 26 November 2025 |
| `ley-para-la-prevencion-y-atencion-socioeconomica-de-las-viol/` | LEY PARA LA PREVENCION Y ATENCION SOCIOECONOMICA DE LAS VIOLENCIAS DEL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 15 September 2017 to 13 February 2026 |
| `ley-para-la-prevencion-mitigacion-e-identificacion-de-riesgo/` | LEY PARA LA PREVENCION, MITIGACION E IDENTIFICACION DE RIESGOS Y RESPONSABILIDADES REFERENTE A INFRAESTRUCTURA ENERGETICA EXISTENTE, PARA PREVER LA SEGURIDAD Y PROTECCION DE LA POBLACION QUE HABITA EN EL ESTADO DE TAMAULIPAS | 1 | as first published: 8 November 2025 |
| `ley-para-la-promocion-del-humanismo-los-valores-y-la-cultura/` | LEY PARA LA PROMOCION DEL HUMANISMO, LOS VALORES Y LA CULTURA DE LA LEGALIDAD -- ANTES LEY PARA LA PROMOCION DE LOS VALORES Y LA CULTURA DE LA LEGALIDAD -- DEL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 18 September 2013 to 22 December 2024 |
| `ley-para-la-proteccion-de-personas-defensoras-de-derechos-hu/` | LEY PARA LA PROTECCION DE PERSONAS DEFENSORAS DE DERECHOS HUMANOS Y PERIODISTAS PARA EL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 2 December 2017 to 15 July 2021 |
| `ley-para-la-proteccion-de-personas-que-intervienen-en-el-pro/` | LEY PARA LA PROTECCION DE PERSONAS QUE INTERVIENEN EN EL PROCEDIMIENTO PENAL DEL ESTADO DE TAMAULIPAS | 3 | as first published, then each reform: 26 May 2015 to 7 June 2023 |
| `ley-para-prevenir-la-tortura-y-otros-tratos-o-penas-crueles/` | LEY PARA PREVENIR LA TORTURA Y OTROS TRATOS O PENAS CRUELES, INHUMANOS O DEGRADANTES EN EL ESTADO DE TAMAULIPAS | 1 | as first published: 20 August 2024 |
| `ley-para-prevenir-y-erradicar-la-discriminacion-en-el-estado/` | LEY PARA PREVENIR Y ERRADICAR LA DISCRIMINACION EN EL ESTADO DE TAMAULIPAS | 16 | as first published, then each reform: 30 December 2004 to 17 January 2026 |
| `ley-para-prevenir-atender-sancionar-y-erradicar-la-violencia/` | LEY PARA PREVENIR, ATENDER, SANCIONAR Y ERRADICAR LA VIOLENCIA CONTRA LAS MUJERES DEL ESTADO DE TAMAULIPAS | 50 | as first published, then each reform: 23 August 2007 to 30 September 2026 |
| `ley-para-prevenir-combatir-y-sancionar-la-trata-de-personas/` | LEY PARA PREVENIR, COMBATIR Y SANCIONAR LA TRATA DE PERSONAS EN EL ESTADO DE TAMAULIPAS | 7 | as first published, then each reform: 20 October 2010 to 7 June 2023 |
| `ley-para-prevenir-investigar-y-sancionar-los-delitos-en-mate/` | LEY PARA PREVENIR, INVESTIGAR Y SANCIONAR LOS DELITOS EN MATERIA DE EXTORSION DEL ESTADO DE TAMAULIPAS | 1 | as first published: 11 December 2025 |
| `ley-para-regular-la-apertura-instalacion-y-funcionamiento-de/` | LEY PARA REGULAR LA APERTURA, INSTALACION Y FUNCIONAMIENTO DE LAS CASAS DE EMPEÑO EN EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 10 January 2019 to 1 January 2025 |
| `ley-para-regular-los-servicios-privados-de-seguridad-en-el-e/` | LEY PARA REGULAR LOS SERVICIOS PRIVADOS DE SEGURIDAD EN EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 9 November 2007 to 13 September 2024 |
| `ley-que-establece-las-bases-normativas-en-materia-de-bandos/` | LEY QUE ESTABLECE LAS BASES NORMATIVAS EN MATERIA DE BANDOS DE POLICIA Y BUEN GOBIERNO PARA EL ESTADO DE TAMAULIPAS | 4 | as first published, then each reform: 15 December 1987 to 7 June 2023 |
| `ley-que-regula-el-aseguramiento-administracion-enajenacion-y/` | LEY QUE REGULA EL ASEGURAMIENTO, ADMINISTRACION, ENAJENACION Y DISPOSICION FINAL DE VEHICULOS AUTOMOTORES, ACCESORIOS O COMPONENTES ABANDONADOS PARA EL ESTADO DE TAMAULIPAS | 6 | as first published, then each reform: 26 November 2014 to 22 December 2024 |
| `ley-que-regula-la-celebracion-de-espectaculos-taurinos-en-el/` | LEY QUE REGULA LA CELEBRACION DE ESPECTACULOS TAURINOS EN EL ESTADO DE TAMAULIPAS | 2 | as first published, then each reform: 19 July 2003 to 22 December 2016 |
| `ley-que-regula-la-integracion-y-operatividad-de-las-sociedad/` | LEY QUE REGULA LA INTEGRACION Y OPERATIVIDAD DE LAS SOCIEDADES MUTUALISTAS PARA EL ESTADO DE TAMAULIPAS | 1 | as first published: 3 March 2004 |
| `ley-reglamentaria-de-las-oficinas-del-registro-civil/` | LEY REGLAMENTARIA DE LAS OFICINAS DEL REGISTRO CIVIL DEL ESTADO DE TAMAULIPAS | 12 | as first published, then each reform: 30 October 1940 to 23 September 2023 |
| `ley-sobre-el-escudo-y-el-himno-de-tamaulipas-antes-ley-del-e/` | LEY SOBRE EL ESCUDO Y EL HIMNO DE TAMAULIPAS -ANTES LEY DEL ESCUDO DE ARMAS Y DEL HIMNO DE TAMAULIPAS- | 12 | as first published, then each reform: 16 March 2005 to 11 June 2026 |
| `ley-sobre-el-regimen-de-propiedad-en-condominio-de-bienes-in/` | LEY SOBRE EL REGIMEN DE PROPIEDAD EN CONDOMINIO DE BIENES INMUEBLES PARA EL ESTADO DE TAMAULIPAS | 5 | as first published, then each reform: 12 June 2003 to 22 December 2021 |
| `ley-sobre-el-sistema-estatal-de-asistencia-social/` | LEY SOBRE EL SISTEMA ESTATAL DE ASISTENCIA SOCIAL | 19 | as first published, then each reform: 19 October 1986 to 3 September 2026 |
| `ley-sobre-la-organizacion-y-funcionamiento-internos-del-cong/` | LEY SOBRE LA ORGANIZACION Y FUNCIONAMIENTO INTERNOS DEL CONGRESO DEL ESTADO DE TAMAULIPAS | 111 | as first published, then each reform: 25 July 2004 to 13 September 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Matamoros, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
