JC = javac
SRCPATH = src
BINPATH = bin
JFLAGS = -d $(BINPATH) -sourcepath $(SRCPATH) -encoding utf8 -cp libs/jsoup-1.9.2.jar;libs/jxl.jar

all:
	@echo Compiling Source Codes From src/ Into bin/
	$(JC) $(JFLAGS) src/launch/Main.java

run:
	java -Dfile.encoding=UTF-8 -cp bin;libs/jsoup-1.9.2.jar;libs/jxl.jar launch.Main

