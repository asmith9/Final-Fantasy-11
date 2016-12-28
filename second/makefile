all:ff_dev

FF11_Devolved.o: FF11_Devolved.cpp
	g++ -c "FF11_Devolved.cpp" -o FF11_Devolved.o

FF11Devolved.o: FF11Devolved.cpp
	g++ -c "FF11Devolved.cpp" -o FF11Devolved.o

functions.o: functions.cpp
	g++ -c "functions.cpp" -o functions.o

ff_dev: FF11_Devolved.o FF11Devolved.o functions.o
	g++ -o ff_dev abilities.o functions.o FF11Devolved.o $(LIBS)
