import 'package:flutter/material.dart';

class SimpleWrapExample extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text("Wrap Products")),
      body: Padding(
        padding: const EdgeInsets.all(16.0),
        child: Wrap(
          spacing: 10,     // space between items (horizontal)
          runSpacing: 10,  // space between lines (vertical)
          children: List.generate(
            10,
            (index) => Container(
              width: 120,
              height: 120,
              color: Colors.blue,
              alignment: Alignment.center,
              child: Text(
                "Item $index",
                style: TextStyle(color: Colors.white),
              ),
            ),
          ),
        ),
      ),
    );
  }
}
