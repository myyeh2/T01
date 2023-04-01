# 精銳矩陣計算求解器(Sharp Matrix Solver, SMS)驗證  

## 測試實例採用 : Ray W Clough & Joseph Penzien, "Dynamics of Structures"  

### 第202頁 至 203頁，作爲SMS實作驗證  

M * y$_h$''(t) + C * y$_h$'(t) + K * y$_h$(t) = 0  . . . . . (A)  

方程式(A)式中，(y$_h$，Subscript h代表Homogeneous Solution)  

已知數據如下:  

$M=\left(\begin{array}{lr}1 & 0 & 0 \\ 0 & 1.5 & 0 \\ 0 & 0 & 2 \end{array}\right)$  

$C=\left(\begin{array}{lr}0 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{array}\right)$  

$K=\left(\begin{array}{lr}600 & -600 & 0 \\-600 & 1800 & -1200 \\ 0 & -1200 & 3000 \end{array}\right)$  

$InitValue=\left[\begin{array}{lr} \ \ 0 \\ \ \ 9 \\ \ \ 0 \\ 0.5 \\ 0.4 \\ 0.3 \end{array} \right]$

其變位，速度，加速度的數值響應值和視覺圖表如所示  

公式(A)與SMS測試的結果完全相同。  
