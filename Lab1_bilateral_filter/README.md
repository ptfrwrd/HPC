# Результаты выполнения лабораторной работы Bilateral Filter (cpu/gpu).

**Время CPU:**  80.58877968788147
**Время GPU**:  0.005403280258178711
**CPU/GPU**: 14914.78802453338

# Иные способы подсчёта времени:

blocksize (1,1,1)

```%load_ext autotime```
CPU:  23.7 s
GPU: 53 ms
CPU/GPU: ~400

```pycuda.driver```
CPU: 23.66973046875
GPU: 0.04375600051879883
CPU/GPU: ~575

```process_time()```
CPU: 23.317948978999993
GPU: 0.04540985200000591
CPU/GPU: 513

blocksize (2,2,1)

```%load_ext autotime```
CPU:  23.7 s
GPU: 24.2 ms ms
CPU/GPU: ~980

```pycuda.driver```
CPU: 23.66973046875
GPU: 0.013681695938110352
CPU/GPU: ~1730

```process_time()```
CPU: 23.317948978999993
GPU: 0.014904685000004747
CPU/GPU: 1564
