# Design Spec for Soc Ops Bingo App - Cozy Coffee Shop Theme

## Overview
Redesigning the Soc Ops bingo app components (StartScreen, GameScreen, BingoBoard, BingoSquare, BingoModal) with a Cozy Coffee Shop theme to create a welcoming, relaxing user experience.

## Theme Elements
- **Colors**: Warm, soft pastels - beige (#F5F5DC), light brown (#D2B48C), cream (#FFFDD0), soft greens (#90EE90)
- **Inspirations**: Coffee mugs, steam, coffee beans
- **Fonts**: Cozy, readable fonts (e.g., serif or script for headings, sans-serif for body)
- **Animations**: Subtle animations like gentle steam rising, soft glows
- **Textures**: Subtle paper or wood textures for a cozy feel
- **Responsiveness**: Ensure mobile-first design
- **Accessibility**: Maintain high contrast ratios, keyboard navigation, screen reader support

## Components to Redesign
- StartScreen
- GameScreen
- BingoBoard
- BingoSquare
- BingoModal

## Iterations
- Iteration 1: Define CSS variables for theme colors and apply to global styles. Updated body background to coffee-beige, font to Georgia serif, and mapped existing color classes to theme variables (e.g., bg-gray-50 to --coffee-beige, bg-accent to --coffee-brown).
- Iteration 2: Update StartScreen with theme colors and coffee elements. Added a coffee mug icon with animated steam rising, and a subtle coffee bean pattern background for a warm, inviting atmosphere. Used SVG for scalability and CSS variables for consistent theming.
- Iteration 3: Update GameScreen with parchment header background using subtle dot texture, theme colors for text (coffee-brown for buttons and instructions, dark-brown for title), and maintained layout with soft pastel accents.
- Iteration 4: Update BingoBoard and BingoSquare.
- Iteration 5: Update BingoModal with parchment background using the .parchment class for a card stock feel, replace celebration emoji with coffee mug icon (☕), maintain warm amber colors, and add a subtle fade-in animation for modal appearance instead of bounce for a more cozy feel.
- Iteration 6: Add subtle animations and textures.
- Iteration 7: Ensure responsiveness and accessibility.

## Decisions and Rationale
- Chose pastels for a calming effect, aligning with coffee shop ambiance.
- Incorporated coffee elements to tie into the theme without overwhelming functionality.
- Prioritized mobile responsiveness to allow play on various devices.
- Maintained accessibility by ensuring color contrasts meet WCAG standards.
