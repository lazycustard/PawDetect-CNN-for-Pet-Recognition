| **CNN Layer**           | **Function in CNN**                                   | **Detective Analogy**                                              |
|-------------------------|--------------------------------------------------------|---------------------------------------------------------------------|
| `Conv2D`                | Detects patterns in small regions of the image         | Using a magnifying glass to look for features like eyes or hats     |
| `MaxPooling2D`          | Reduces size, keeps strongest features                 | Focusing only on the most obvious clues, ignoring noise             |
| `Conv2D` (again)        | Detects more complex patterns from earlier features    | Combining earlier clues to find full shapes like faces              |
| `MaxPooling2D` (again)  | Reduces size again to simplify further                 | Summarizing the important parts of those combined clues             |
| `Flatten`               | Converts 2D data to 1D vector                          | Writing down all the clues into a flat list for analysis            |
| `Dense (128 units)`     | Learns and connects patterns in features               | Detective thinking deeply about how clues are connected             |
| `Dense (1 unit + sigmoid)` | Outputs probability between 0 and 1 (binary output) | Making a final yes/no decision (Is this a criminal or not?)         |
