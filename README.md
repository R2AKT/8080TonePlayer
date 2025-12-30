Playing music through the generation of a tone signal on the INTE pin by the EI/DI commands for the 580VM80a (i8080a) processor.
The music is recorded in 3 arrays of type UINT16:
- frequencies of the tones being played;
- durations of the tones being played;
- pause between the tones being played.
  
 A zero playback time value indicates the end of the music.
 Optimized for a 2.5 MHz processor frequency, for other frequencies, the tone and delay calculation constants must be replaced.


Воспроизведение музыкальных произведений через генерацию тонального сигнала на пине INTE командами EI/DI для процессора 580ВМ80а (i8080а).
Музыкальное произведение записывается в 3 массива типа UINT16:
- частоты воспроизводимых тонов;
- длительности воспроизводимых тонов;
- пауза между воспроизводимыми тонами.
  
  Нулевое значение времени воспроизведения означает конец музыкального произведения.
  Оптимизированно для частоты процессора 2.5МГц, при иной частоте необходимо заменить константы вычисления тона и задержек.
