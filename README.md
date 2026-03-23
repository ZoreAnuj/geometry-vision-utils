# geometry-vision-utils

A Rust library for 2D and 3D geometric transformations, tailored for computer vision and robotics applications. It provides essential tools for handling rotations, poses, and projections, serving as a foundational utility for building robust perception and state estimation systems.

## Key Features
*   **Lie Group Operations:** Implementations for SO(3), SE(3), and Sim(3) groups with efficient interpolation and perturbation.
*   **Projective Geometry:** Utilities for camera models, point projections, and fundamental matrix computations.
*   **Numerical Stability:** Carefully designed to handle singularities and edge cases common in geometric computations.

## Tech Stack
*   Rust
*   `nalgebra` for linear algebra
*   `num-traits` for generic numeric operations

## Getting Started
Add the dependency to your `Cargo.toml`:
```toml
[dependencies]
geometry-vision-utils = "0.1"
```
Import and use the library in your code:
```rust
use geometry_vision_utils::se3::SE3;
```