RELEASE NOTES
********************************************************************************
To deploy this module, please use Module Management utility from OpenCMS
Administration View.

This module comes with limitations, due to french language bad handling by
javascript applications like JsCalendar or FCKEditor. After installing the
module, it will be hard to set TimeWarp and FCKEditor will display traduction
errors.

Nowadays the best way to solve that is to overwrite "Fr" localisation files
with a renamed copy of "En" localisation files.
See files :
- /system/workplace/resources/components/js_calendar/lang/calendar-fr.js
- /system/workplace/resources/editors/fckeditor/editor/lang/fr.js


NOTES DE VERSION
********************************************************************************
Pour d�ployer ce module, veuillez faire appel � l'utilitaire de Gestion de
Module de l'Administration d'OpenCMS.

Ce module pr�sente 2 limites, li�es � une mauvaise prise en charge de la langue
Fran�aise par les applications Javascript JsCalendar et FCKEditor. Ainsi, apr�s
installation du module il devient complexe de fixer une TimeWarp, et FCKEditor
contient des erreurs de traduction.

La meilleurs solution � ce jour consiste � �craser les fichiers de traduction
"Fr" par une copie renomm�e des fichiers de traduction "En".
Voir les fichiers :
- /system/workplace/resources/components/js_calendar/lang/calendar-fr.js
- /system/workplace/resources/editors/fckeditor/editor/lang/fr.js