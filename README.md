# math-vim
Some useful key bindings for typing Unicode mathematics

Source math.vim when you start vim

Use `:Mon` to enable the bindings and `:Moff` to disable them.

Some examples:

1. To get〈ψ|∂⃡|ϕ〉type \<\psi|\partial\^<->|\phi\>
2. To get x⃗·y⃗ = ∑ᵢxᵢyᵢ type x\^->\.y\^-> = \sum\_ix\_iy\_i
3. To get ∫∏ᵢdxᵢexp(-½xᵢ²) type \int\prod\_idx\_iexp(-\1/2x\_i\^2)
4. To get ∬dω = ∮ω type \iintd\omega = \oint\omega
5. To get … → H̃₀(A∩B) → H̃₀(A)⊕H̃₀(B) → H̃₀(X) → 0 type...well you can...but I don't know how to stop github markup interfering.

Have a look in math.vim for the rest.

Note that the expressions above won't display correctly if you don't have suitable fonts installed.
