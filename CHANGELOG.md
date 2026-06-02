# Changelog

## [0.1.0.0] - 2026-06-02

### Added
- Classic Snake game as a single-file HTML application — open in any browser and play instantly
- 20x20 grid with Canvas rendering at 60fps and 100ms game tick for authentic retro feel
- Keyboard controls (arrow keys and WASD) with direction queue to prevent accidental reversals
- Touch d-pad for mobile play with drag support via touchmove + elementFromPoint
- Particle effects on food collection with per-frame animation
- HiDPI/Retina display support via devicePixelRatio scaling
- Responsive layout adapting to mobile viewports down to 320px
- Game state machine: waiting, playing, game over, and win states
- Score tracking and game-over overlay with instant restart
- Tab visibility handling to prevent time-warp on resume
