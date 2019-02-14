# old-mitsuba-dependencies

Files for use mitsuba in old intel processors in windows. Tested on an i7-3770

1- Add files to dependendencies  
2- Compile mitsuba  
3- Duplicate and change the name of these DLL on dist folder  
   * Half.dll -> Half-2_3.dll  
   * zlib1.dll -> zlib.dll  
   
If you clean the build woth scons the these DLL won't be removed so you won't need to rename any more. 
