
# My Flutter notes

## Topics

 - [Remove debug banner](#Remove-debug-banner)
 - [Automatically formatting code ](#Automatically-formatting-code )

## Remove debug banner

To remove debug banner from simulator.

```bash
  debugShowCheckedModeBanner: false,
```


#### Usage/Examples

```flutter
void main() {
  runApp(
    MaterialApp(
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        backgroundColor: Colors.teal,
        body: Container(),
      ),
    ),
  );
}
```

## Automatically formatting code 

#### Automatically formatting code in Android Studio and IntelliJ

- In macOS, press ` Cmd + Option + L.`
- In Windows and Linux, press ` Ctrl + Alt + L.`
(For to automatically format the code u shoud add ` , ` after the ` )`.)


