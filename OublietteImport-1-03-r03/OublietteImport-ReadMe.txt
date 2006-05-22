This is an Oubliette (http://oubliette.sf.net/) import plug-in for KeePass
(http://keepass.sf.net/). The plug-in currently only works when compiled with
VC71 (although it compiles without errors in VC60). However, using a VC71
plug-in with KeePass (which is currently compiled with VC60) causes some
minor issues regarding the GUI integration:

- The plug-in is only visible under "Extras", not in the "File" -> "Import From"
  menu. If you get no such menu entry under "Extras" you are probably using a
  newer version of KeePass than the plug-in was compiled for. In that case
  please wait for an updated plug-in.

- The menu entry is always enabled, even if there is not database open to import
  to.

- The database to import to is not marked as modified after importing, so
  remember to save it :-)

I hope you find this plug-in still useful.

Sebastian Schuberth <sschuberth@gmail.com>
2006.may.22
