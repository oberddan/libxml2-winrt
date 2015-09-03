# libxml2-winrt
libxml2 static to winrt; version XGH... please constribute

- Line from configure like:
cscript configure.js cruntime=/MTd ftp=no http=no html=no docb=no iconv=no iso8859x=yes xml_debug=no zlib=yes static=yes debug=? prefix=.\installd64 lib=..\zlib\winrt\x64\debug include=..\include;..\zlib\win32\include
- Don't forget change your zlib patch
- Threads Winrt from Shawn Hargreaves Blog (http://blogs.msdn.com/b/shawnhar/archive/2012/03/12/createthread-for-windows-8-metro.aspx?PageIndex=2)

