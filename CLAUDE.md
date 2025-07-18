# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a static HTML documentation project for the "Tangnet Field Science Lab Radium Clock Project" - a collection of vintage radium clocks with educational content about radiation safety and the historical "Radium Girls" tragedy.

## Technology Stack
- Pure HTML5 with inline CSS
- No JavaScript frameworks or build tools
- No package management or dependencies
- Static files that can be opened directly in a browser

## Development Commands
This is a simple static HTML project with no build pipeline:
- **View**: Open HTML files directly in a web browser
- **Edit**: Modify HTML files with any text editor
- **Deploy**: Copy files to any web server (no build step required)

## Architecture & Structure

### Core Pages
- `bradleyradium1.html` - Documents a 1955 radioactive Bradley clock (700+ CPM)
- `brandleynoradium1.html` - Documents a 1970s non-radioactive Linden clock
- `clockrepair.html` - Clock repair and maintenance guide
- `historydesignskeleton.html` - Historical context about radium in clockmaking
- `initialdisplayplans.html` - Plans for physical display cabinet with Geiger counter integration

### Key Design Elements
- Retro terminal/CRT aesthetic with green-on-black color scheme
- CSS animations for typing effects and glowing text
- ASCII art borders and decorative elements
- Consistent styling across all pages using inline CSS

### Important Considerations
1. **Radiation Safety**: All content involving radioactive clocks includes proper safety warnings and CPM readings
2. **Educational Focus**: Balance between technical accuracy and engaging presentation
3. **Visual Consistency**: Maintain the cyberpunk/terminal aesthetic across all pages
4. **Self-Contained**: Each HTML file includes all necessary CSS inline - no external stylesheets

## Future Development Plans
The project includes plans for:
- Physical display cabinet with live Geiger counter readout
- Raspberry Pi integration for serving web content
- Environmental monitoring capabilities
- LED lighting effects synchronized with radiation readings