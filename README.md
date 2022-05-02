# ReportGenerator

You can also use the c ++ multi-platform library called limeReport to build reports from your  databases.
 Library GitHub link **[GitHub](https://github.com/fralx/LimeReport.git)**

## use and work
1. download github
2. build limeReport to your **Qt version**
3. use directory build and use file *.so  in linux or *.a in windows 
4. **Add library in .pro file and include**

### code in qt
 Add **qml , quick ,printsupport ,xml** to .pro
 add library
 
 `#include  <LimeReport>`
 
  add **Mainwindow.h**
  
  `  LimeReport::ReportEngine  report;`
  
  designReport
  `report.designReport();`
 
	 

