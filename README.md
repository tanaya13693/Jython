# Jython

About Repo: 
-Run python scripts from Eclipse

Steps:
1. Download Python 2.7+ Windows x86-64 MSI (link: https://www.python.org/downloads/release/python-2715/). Run the .exe for installation.
  Quick check for install through cmd: python --version
  
2. Install PyDev through plug-in:
  Go to eclipse->help->new software->http://www.pydev.org/updates-> Accept the license -> installed!
  
3. Download Jython interpreter library:
  jython-standalone-2.5.4-rc1.jar
  
4. Configure Jython in eclipse:
  a. Windows->Preferences->PyDev->Jython Interpreter -> new -> GIve name as 'JI', Browse to .jar file downloaded in step3
  b. Proceed (Even after error will be prompted for 'stdlib not found'). Let it proceed.
  c. Libraries -> New folder -> Add following:
  C:\Python27\Lib
  C:\Python27\libs

5. Add jython jar in build path as well.
  Configuration is done!
  
6. Refer to Hello.py for quick test. 
  
