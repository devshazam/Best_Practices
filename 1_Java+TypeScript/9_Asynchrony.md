# Loop (https://medium.com/@moucodes/exploring-the-difference-between-using-async-await-in-a-for-loop-and-foreach-739c9ebeb64a)
    - for(){ await...}
        - В цикле for итерации выполняются последовательно. Циктл for гарантирует что асинхранная функция будет выполненна последовательно от перкой к последующим
    - arr.forEach((e) => await...)
        - В цикле forEach итерации выполняются одновременно, превая выполнится более быстрая