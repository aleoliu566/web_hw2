1. [15 points] 
Compute the precision, recall, fallout, F1, and average precision for this result.
<br>

|               | relevant | not relevant |    |
|:---           |:------:  |:---:         |:---:|
| retrieved     | 4        | 4            |8
| not retrieved | 6        | 86           |92
|               | 10       | 90           |100

precision = $\dfrac{4}{8}$
recall = $\dfrac{4}{10}$

fallout = $\dfrac{|\{non-relavant\} ∩ \{retrieved\ document \}|}{|{non-relevant\ documents}|}$

fallout = $\dfrac{2}{45}$
F1 = $\dfrac{2\times \dfrac{4}{8} \times \dfrac{4}{10}}{\dfrac{4}{8} + \dfrac{4}{10}}$ = $\dfrac{4}{9}$

$[\ +\ -\ \ -\ \ \ \ +\ \ \ +\  -\  -\ \ +\ ]$
$[\ \ 1,\ 0.5,0.33,0.5,0.6,0.5,\dfrac{3}{7},0.5\ \ ]$

average precision = $\dfrac{1+0.5+0.6+0.5}{4}$ = 0.65


- What is the precision at the recall level of 0.15 according to 11-point interpolated?
