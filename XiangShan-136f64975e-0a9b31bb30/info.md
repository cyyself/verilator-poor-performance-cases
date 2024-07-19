# Performance

Poor performance on Intel 13900K and AMD 7950X3D

Both 37s -> 50s

5x branch miss predict on AMD 7950X3D
8x branch miss predict on Intel 13900K

# Commit

Known good commit: [a2489e3a8d85c95ed0adab605311da1339550c7a](https://github.com/cyyself/llvm-project/commit/a2489e3a8d85c95ed0adab605311da1339550c7a)

known bad commit: [40529f8114e2139748ce075539573e36c2bb281b](https://github.com/cyyself/llvm-project/commit/40529f8114e2139748ce075539573e36c2bb281b)
