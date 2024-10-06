+++
title = "hello, world!"
date = 2024-10-06

[taxonomies]
categories = ["programming"]

[extra]
lang = "en"
toc = false
math = true
mermaid = true
+++

what kind of things can I render?

$$ e^{i\pi} + 1 = 0 $$

<div style="text-align: center;">
{% mermaid() %}
graph TD
    Expr[Expression]
    Expr --> Mult[*]
    Mult --> Add[+]
    Mult --> Num3[4]
    Add --> Num1[2]
    Add --> Num2[3]
{% end %}
</div>

```rust
fn fibonacci(n: u32) -> u32 {
    match n {
        0 => 0,
        1 => 1,
        _ => fibonacci(n - 1) + fibonacci(n - 2),
    }
}
```
