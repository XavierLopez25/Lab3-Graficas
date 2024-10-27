# Lab3-Graficas

This project is a 3D graphics engine implemented in Rust. It uses the `minifb` library for window management and the `nalgebra-glm` library for linear algebra operations. The engine supports loading and rendering 3D models in the OBJ format, and includes basic camera controls for navigating the scene.

## Video demo of my ship:

## Features

- **OBJ Model Loading**: Load and render 3D models in the OBJ format.
- **Camera Controls**: Move and rotate the camera to explore the 3D scene.
- **Basic Shading**: Apply basic lighting to the models.

## Controls

### Camera Movement

- **Orbit Controls**:

  - `Left Arrow`: Rotate the camera left around the model.
  - `Right Arrow`: Rotate the camera right around the model.
  - `W`: Rotate the camera up.
  - `S`: Rotate the camera down.

- **Movement Controls**:

  - `A`: Move the camera left.
  - `D`: Move the camera right.
  - `Q`: Move the camera up.
  - `E`: Move the camera down.

- **Zoom Controls**:
  - `Up Arrow`: Zoom in.
  - `Down Arrow`: Zoom out.

## Dependencies

- `minifb = "0.27.0"`
- `nalgebra-glm = "0.19.0"`
- `tobj = "4.0.2"`

## How to Run

1. Ensure you have Rust installed. If not, download and install it from [rust-lang.org](https://www.rust-lang.org/).
2. Clone this repository.
3. Navigate to the project directory.
4. Run the project using `cargo run`.

```sh
git clone https://github.com/XavierLopez25/Lab3-Graficas.git
cd Lab3-Graficas
cargo build --release
cargo run --release
```
