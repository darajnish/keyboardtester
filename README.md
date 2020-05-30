# Keyboard Tester
A simple Keyboard Tester in Java to help you while cheking an old or damaged keyboard, to know which keys are working.

## Building (using ant)

Requirements:
- JDK 11
- Apache Ant 1.10.4 (or above)

The project can be compiled and built using [Netbeans IDE](https://netbeans.apache.org/) as it's the base IDE used for this project. However, apache ant can be used to compile and build the sources. The java executable (jar) can be built directly with `ant` using,
```bash
ant jar
```
The built java executable (jar) will be available at `dist/KeyboardTester.jar`

## Running

If java is integrated in the desktop envirnmont, you can directly double click the jar file to run it.
You can also run the java executable through command line,
```bash
java -jar dist/KeyboardTester.jar
```

## License
This project is under [MIT License](LICENSE)
