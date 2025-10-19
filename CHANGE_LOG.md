# Change Log

All notable changes to the Interactive Diwali Celebration Page will be documented in this file.

## [1.2.1] - 2025-10-19

### Fixed
- **Dark Mode Background Color**: Fixed dark mode to use solid black (#000000) background
  - All dark mode variants (burst, night, and light modes) now display with pure black background
  - Removed gradients in dark mode for consistent black appearance
  - Improves true dark mode experience and reduces eye strain

## [1.2.0] - 2025-10-17

### Fixed
- **Dark Theme Background**: Dark theme now properly sets the page background to black/very dark colors
  - Burst mode background: Black to dark navy gradient
  - Night mode background: Pure black to dark gradient
  - Light mode background: Dark gray gradient
  - Provides better contrast and true dark mode experience

### Added
- **Auto-firing Rockets and Bombs in Burst Mode**: Burst mode now features automatic firework effects
  - Rockets: Pointed projectiles that launch upward and explode at peak height
  - Bombs: Round projectiles with fuses that create multi-burst explosions
  - 1-3 rockets/bombs fire automatically every 1.5 seconds
  - Each rocket/bomb has a colorful trail effect
  - Explosions create spectacular particle bursts (100+ particles per explosion)
  - Bombs create triple explosions for enhanced visual impact
  - Physics-based trajectories with gravity and velocity
  - Random colors for each rocket/bomb (red, orange, yellow, green, blue, purple, pink)

### Improved
- Enhanced burst mode visual experience with continuous fireworks
- Better dark theme contrast across all celebration modes
- More engaging automatic effects requiring less user interaction

## [1.1.0] - 2025-10-17

### Added
- **Light/Dark Theme Toggle**: User can now switch between light and dark themes
  - Theme toggle button in the top-right corner
  - Smooth theme transitions with CSS variables
  - Theme preference persisted in localStorage
  - Dynamic theme icons (🌙 for dark, ☀️ for light)
  - Theme affects:
    - Background overlays and glass morphism effects
    - Text colors for better readability
    - Control panel styling
    - Title and instruction text
  - Independent from celebration modes (works with all modes)
  - Accessible with proper ARIA labels
  
### Improved
- Enhanced UI accessibility with theme options
- Better contrast and readability in both themes
- Modernized color system using CSS custom properties
- Improved glass morphism effects for both light and dark modes

## [1.0.0] - 2025-10-17

### Added
- Initial release of Interactive Diwali Celebration Page
- **Burst Mode**: Interactive cracker burst effects
  - Click-to-burst functionality with 100+ colorful particles
  - Physics-based particle system with gravity
  - Random ambient crackers for continuous effect
  - Multi-colored explosion patterns (red, orange, yellow, green, blue, purple, pink)
  
- **Night Mode**: Glittering sparkle effects
  - Click-to-sparkle with animated rays
  - Interactive cursor trail effect
  - Glow and shadow effects for sparkles
  - Ambient sparkles appearing randomly across screen
  - Rotating sparkle rays for enhanced visual appeal

- **Light Mode**: Traditional Diwali diya lighting
  - Click-to-light diyas (oil lamps)
  - Realistic flame animations with flickering effect
  - Warm gradient flames (yellow to orange to red)
  - Glowing aura around each flame
  - Detailed diya design with base and rim
  - Smooth flame swaying animation

- **User Interface**:
  - Modern glass morphism design for control panel
  - Three mode selection buttons with gradient styling
  - Active mode indicator
  - Responsive design for all screen sizes
  - Glowing title with animation
  - Helpful instruction text
  - Smooth transitions between modes

- **Technical Features**:
  - HTML5 Canvas rendering engine
  - 60 FPS animation loop
  - Efficient particle management system
  - Dynamic gradient backgrounds for each mode
  - Shadow and glow effects
  - No external dependencies (pure vanilla JavaScript)

### Features
- Full-screen interactive canvas
- Real-time particle rendering
- Multiple particle systems (burst, sparkle, diya)
- Cursor-based interactions
- Mode switching functionality
- Ambient effects for enhanced atmosphere
- Responsive layout

### Design
- Custom color schemes for each mode
- Gradient backgrounds
- Glass morphism UI elements
- Smooth hover effects on buttons
- Animated text effects
- Professional typography

---

## Future Enhancements (Planned)
- Sound effects for each mode
- Mobile touch gesture support
- Additional celebration modes (rangoli, fireworks)
- Customizable particle colors
- Save favorite patterns
- Social sharing functionality
