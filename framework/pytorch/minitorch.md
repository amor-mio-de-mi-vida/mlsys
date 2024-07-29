# Minitorch

我的实现链接在 [https://github.com/amor-mio-de-mi-vida/mini-torch]()

## Task 0

## Task 1

Task 1.3 chain rule

```python
def chain_rule(self, d_output: Any) -> Iterable[Tuple[Variable, Any]]:
        h = self.history
        assert h is not None
        assert h.last_fn is not None
        assert h.ctx is not None

        grads = h.last_fn._backward(h.ctx, d_output)
        return zip(h.inputs, grads)
```

Task 1.4 topological_sort

Task 1.4 backpropagate

## Task2

Task 2.2 broadcast_index



Task 2.3 tensor_reduce


Task 2.4 Permute 类中的 backward 



## Task 3

Task 3.2 Matrix_Multiply



Task 3.3  sum_practice

共享内存怎么用？cuda的使用还需要时间去琢磨
