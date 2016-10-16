This compiles with jar available at path and stores the classfiles in bin folder
javac -cp $PI4J_LIB/'*' -d bin/ DistanceMonitor.java

This command executes the files binding bin and the PI4J_Classpath
sudo java -cp $PI4J_LIB/'*':bin/ DistanceMonitor
