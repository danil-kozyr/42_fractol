# 42_fractol

A fractal visualization project that renders mathematical fractals in real-time with interactive zoom and navigation, created as part of the 42 School curriculum.

## 📖 About

**Fractol** generates and displays fractal sets including Mandelbrot, Julia, and Burning Ship fractals using complex mathematical calculations and real-time rendering techniques.

## 🚀 Features

- **Multiple Fractal Types**: Mandelbrot, Julia, and Burning Ship fractals
- **Real-time Rendering**: Smooth fractal generation and display
- **Interactive Navigation**: Zoom, pan, and explore fractal details
- **Color Schemes**: Multiple color palettes for enhanced visualization
- **Optimized Calculations**: Efficient mathematical computations
- **Mouse Integration**: Zoom and navigation with mouse controls

## 🔧 Build Instructions

### Prerequisites

- GCC compiler, Make
- MinilibX graphics library (included)
- libft library (included)

### Compilation

```bash
make                # Build the project
make clean         # Clean object files
make fclean        # Clean everything
make re            # Rebuild everything
```

## 📝 Usage

```bash
# Mandelbrot fractal
./fractol mandelbrot

# Julia fractal with parameters
./fractol julia -0.7 0.27015

# Burning Ship fractal
./fractol burningship
```

### Controls

- **Mouse Wheel**: Zoom in/out
- **Mouse Click**: Center view on point
- **Arrow Keys**: Navigate fractal
- **+/-**: Adjust iteration depth
- **C**: Cycle through color schemes
- **ESC**: Exit

### Fractal Types

- **Mandelbrot**: Classic fractal set z² + c
- **Julia**: Filled Julia sets with customizable parameters
- **Burning Ship**: Variant with absolute value operations

## 🔍 Implementation Details

### Mathematical Foundation

- **Complex Numbers**: Using real and imaginary components
- **Iteration Formula**: z(n+1) = z(n)² + c
- **Convergence Testing**: Determining if points escape to infinity
- **Color Mapping**: Converting iteration counts to colors

### Optimization Techniques

- **Escape Radius**: Early termination for divergent sequences
- **Iteration Limits**: Configurable maximum iterations
- **Pixel Mapping**: Efficient screen-to-complex plane conversion
- **Color Interpolation**: Smooth color transitions

### Rendering System

Real-time pixel-by-pixel calculation with optimized mathematical operations and smooth color gradients.

## 🧪 Testing

```bash
# Test different fractals
./fractol mandelbrot
./fractol julia -0.4 0.6
./fractol julia 0.285 0.01
./fractol burningship

# Interactive exploration
# Use mouse wheel to zoom into interesting areas
# Try different Julia parameters for varied patterns
```

## 🎨 Color Schemes

Multiple color palettes available:

- **Classic**: Traditional fractal colors
- **Psychedelic**: Vibrant rainbow colors
- **Monochrome**: Black and white gradients
- **Fire**: Red, orange, yellow gradients

## 🔗 Dependencies

- **libft**: Custom C library for basic functions
- **MinilibX**: Graphics library for window management and rendering
- **Math Library**: Complex number calculations and trigonometry

---

_Mathematical visualization project demonstrating fractal geometry, complex number calculations, and real-time graphics rendering._
