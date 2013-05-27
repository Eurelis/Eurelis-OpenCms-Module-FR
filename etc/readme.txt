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
Pour déployer ce module, veuillez faire appel à l'utilitaire de Gestion de
Module de l'Administration d'OpenCMS.

Ce module présente 2 limites, liées à une mauvaise prise en charge de la langue
Française par les applications Javascript JsCalendar et FCKEditor. Ainsi, après
installation du module il devient complexe de fixer une TimeWarp, et FCKEditor
contient des erreurs de traduction.

La meilleurs solution à ce jour consiste à écraser les fichiers de traduction
"Fr" par une copie renommée des fichiers de traduction "En".
Voir les fichiers :
- /system/workplace/resources/components/js_calendar/lang/calendar-fr.js
- /system/workplace/resources/editors/fckeditor/editor/lang/fr.js