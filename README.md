# A Style Guide for Modernist Design 

## Table of Contents

1. [Layout](#layout)
2. [Typography](#typography)
3. [Colors](#colors)
4. [Gradients](#gradients)
5. [Shadows](#shadows)
6. [Motion](#motion)

## Layout

<a name="typography"></a>
## Typography

### Rules

  <a name="typography--type-count"></a><a name="3.1"></a>
  - [3.1](#typography--type-count) Never use more than three typefaces on a page at once.

    > Why? A range of typefaces used on a single page does demonstrates a poorly-defined brand and can appear lazy and cluttered. At most, three different typefaces may be used at once (logo, headers, body content).
    
  <a name="typography--stylistic-fonts"></a><a name="3.2"></a>
  
  - [3.2](#typography--stylistic-fonts) Reserve stylistic fonts for logo use only.
    - This rule is kind of broad, as there are always edge cases, but in general you should stick to using stylistic fonts (any kind of curly, curvy, or novelty font) for logos only. Take Linguistic for example, which uses Lily Script One for its logo but uses Lato / Proxima Nova in for all other text.

  <a name="typography--type-hierarchy"></a><a name="3.3"></a>
  - [3.3](#typography--type-hierarchy) Maintain a consistent type hierarchy. You should only ever be using a handful of font sizes and one or two font weights to develop type hierarchy. Think of the HTML header tags h1, h2, h3, etc. You should have distinct visual styles for at least four of them, using variations in brightness, size, and weight to denote the importance of text. For a terrific example of type hierarchy, check out Apple's Human Interface Guidelines.

  - [3.4] Keep your body text a normal weight and well-spaced. Text should always be legible, so reserve light or bold fonts for large headers or cases in which the font weight will have little impact on the legibility of text. Additionally, always keep the line spacing of your body text at 1.15 to 1.5 (depending on size) to maximize legibility. For example, this article has roughly a 1.5 rem line spacing. Justifying your body paragraphs doesn't hurt, either.

## Colors

### Rules 
  <a name="color--body-background"></a><a name="3.1"></a>
  - [3.1](#color--body-background) Body backgrounds should always be shade of gray
	
    > Why? Colored backgrounds, even very dark grays, can easily create a strain on the eyes. For important content such as the text body of a webpage or application, it is crucial users can read and intepret the page with ease.

  <a name="color--hero-background"></a><a name="3.2"></a>
  - [3.2](#color--hero-background) Only use colored or gradient backgrounds on sections designed to draw the user's attention. For example, headers, heroes, call-to-action banners, etc.

  <a name="color--white-text"></a><a name="3.3"></a>
  - [3.3](#color--white-text) In most cases, use white text on any image, colored, or gradient background. If needed, apply a very light  drop shadow (<= 10% opacity) to the text.

    > Why? White-on-dark is often more aethetically appealing and easier to create variants for. Deciding on a dark color to use against a colored background can often be challenging. However, make sure that whatever color combo you choose is [accessible](#accessibility) as well.

  <a name="color--absolute-blacks"></a><a name="3.4"></a>
  - [3.4](#color--absolute-blacks) Never use absolute blacks. 

    > Why? Pure, opaque black (#000) is often too harsh for most webpages. Even GitHub's body font color is #24292e, not #000. When in doubt, you can use numerical web-safe grayscale hex codes (#111, #222 ... #aaa, #bbb, and so on).

  <a name="color--complements"></a><a name="3.4"></a>
  - 3.5 Ensure colored components do not border each other. 

    > Why? Unless the colors are very strong complements of one another, often times the contrast of two neighboring colors can create a sense of polarization and division that breaks the flow of your page. In the case of where a navigation bar might touch a colored hero, opt for a transparent navbar background instead.

## Gradients
## Shadows

Ensure consistency across all components. Once you've defined a light source for your page, ensure that all shadows follow its direction. If light is "hitting" your page at 135 degrees, then every shadow and gradient should fall at 135 degrees.
Use shadows as a tool to present hierarchy or state. Shadows should be used to either highlight page components, provide page structure, or depict state. For example, you can depict a button is pressed by lowering its elevation as opposed to changing its color. Too many shadows can present too much dimensionality, so be careful (e.g. don't create a site with 18 unique elevations).
Your shadow's offset should equal roughly half of its blur radius. For example, a shadow with an x / y offset of 10px should have a blur radius of roughly 20px. This approach renders the most authentic shadow.
Always keep the opacity of shadows to under 25%. Err on the side of subtlety so not to detract from your design. If you are using a dark background, in some cases you may need to bump up the opacity of your shadow in order to ensure its visibility.
Shadows don't always need to be black. When using shadows on colored surfaces, it is often advantageous to use a very dark or dulled variant of the background color to improve the shadow's blend.

## Hierarchy
## Motion
