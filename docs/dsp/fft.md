我们定义离散傅里叶变换 (DFT) 为：

$$ X[k] = \sum_{n=0}^{N-1} x[n] e^{-j \frac{2\pi}{N} kn} $$

```
// 这是一个计数器
module counter(
    input clk,
    output reg [3:0] out
);
    always @(posedge clk) begin
        out <= out + 1;
    end
endmodule
```