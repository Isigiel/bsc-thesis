# Recursive call _fibonacci_

Testing project can be found in the `code` folder.

## Code in test function
```cpp
WASM_EXPORT
uint32_t run(uint32_t n) {
    if (n < 2) {
        return n;
    }
    return run(n - 1) + run(n - 2);
}
```
Calculates the nth fibonacci number using recursive calls.

## Results
Following are the average runtimes of on call in microseconds

`Wasm3 v0.4.6 on ESP32, build Feb 17 2020 15:42:11`   
`Setup time: 1260`
|Run    |WASM   |NATIVE |
|---    |---    |---    |
|1      |41773  |1002   |
|2      |41767  |1001   |
|3      |41766  |1000   |
|4      |41766  |1000   |
|5      |41766  |1000   |
|6      |41766  |1000   |
|7      |41767  |1000   |
|8      |41766  |1000   |
|9      |41766  |1000   |
|10     |41766  |1000   |
|11     |41767  |1000   |
|12     |41766  |1000   |
|13     |41767  |1000   |
|14     |41766  |1000   |
|15     |41767  |1000   |
|16     |41766  |1000   |
|17     |41766  |1000   |
|18     |41766  |1000   |
|19     |41766  |1000   |
|20     |41766  |1001   |
|21     |41767  |1000   |
|22     |41766  |1000   |
|23     |41766  |1000   |
|24     |41766  |1000   |
|25     |41766  |1000   |
|26     |41767  |1000   |
|27     |41766  |1000   |
|28     |41766  |1000   |
|29     |41766  |1000   |
|30     |41766  |1000   |
|31     |41766  |1000   |
|32     |41766  |1000   |
|33     |41766  |1000   |
|34     |41766  |1000   |
|35     |41766  |1000   |
|36     |41767  |1000   |
|37     |41767  |1000   |
|38     |41766  |1000   |
|39     |41766  |1000   |
|40     |41766  |1000   |
|41     |41766  |1000   |
|42     |41766  |1001   |
|43     |41767  |1000   |
|44     |41766  |1000   |
|45     |41767  |1000   |
|46     |41766  |1000   |
|47     |41766  |1000   |
|48     |41766  |1000   |
|49     |41766  |1000   |
|50     |41766  |1000   |
|51     |41767  |1000   |
|52     |41766  |1000   |
|53     |41766  |1000   |
|54     |41766  |1000   |
|55     |41766  |1000   |
|56     |41766  |1000   |
|57     |41766  |1000   |
|58     |41766  |1000   |
|59     |41766  |1000   |
|60     |41766  |1000   |
|61     |41766  |1000   |
|62     |41766  |1000   |
|63     |41766  |1000   |
|64     |41767  |1001   |
|65     |41766  |1000   |
|66     |41767  |1000   |
|67     |41767  |1000   |
|68     |41766  |1000   |
|69     |41766  |1000   |
|70     |41766  |1000   |
|71     |41767  |1000   |
|72     |41766  |1000   |
|73     |41766  |1000   |
|74     |41766  |1000   |
|75     |41766  |1000   |
|76     |41766  |1000   |
|77     |41766  |1000   |
|78     |41766  |1000   |
|79     |41766  |1000   |
|80     |41766  |1000   |
|81     |41766  |1000   |
|82     |41767  |1000   |
|83     |41766  |1000   |
|84     |41766  |1000   |
|85     |41766  |1000   |
|86     |41767  |1000   |
|87     |41766  |1000   |
|88     |41767  |1000   |
|89     |41766  |1000   |
|90     |41766  |1000   |
|91     |41766  |1000   |
|92     |41766  |1000   |
|93     |41766  |1000   |
|94     |41766  |1000   |
|95     |41767  |1000   |
|96     |41767  |1000   |
|97     |41766  |1000   |
|98     |41766  |1000   |
|99     |41766  |1000   |
|100    |41766  |1000   |


