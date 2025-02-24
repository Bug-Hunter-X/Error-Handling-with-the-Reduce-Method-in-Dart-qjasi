# Error Handling with the Reduce Method in Dart

This repository demonstrates an uncommon error that can occur when using the `reduce` method in Dart. The `reduce` method is useful for accumulating a result from a list of values. However, it throws a `StateError` if the list is empty.  This simple example showcases the issue and provides a solution.

## Bug Description
The `reduce` method requires at least one element in the list; otherwise, it throws a `StateError` exception.  This is not immediately obvious and can easily lead to runtime errors if not handled properly.

## Bug Solution
The solution involves adding a check to ensure the list is not empty before applying the `reduce` method. If empty, a default value should be returned, preventing the error.

## How to run
1. Clone this repository.
2. Run the example using Dart's `dart run` command.