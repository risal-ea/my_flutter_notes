
# My Flutter notes




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
}
```

