all: TextTrader.exe
TextTrader.exe:
	cl /DWIN32 /I ..\..\PDCurses /I ..\..\CTP /I ..\..\INIReader ..\..\TextTrader.cpp ..\..\INIReader\INIReader.cpp ..\..\INIReader\ini.c /link /LIBPATH:..\..\PDCurses /LIBPATH:..\..\CTP thostmduserapi_se.lib thosttraderapi_se.lib pdcurses.lib advapi32.lib user32.lib /OUT:TextTrader.exe
clean:
	del *.obj TextTrader.exe
