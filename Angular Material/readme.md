Themes convey meaning through color, tones, and contrasts. And the theme color palettes, alphas, and shadows deliver a consistent tone to your application and a unified feel for all Angular Material UI components. Theming allows developers to change the intention and meaning of the application by changing the colors and shadows.

Accessibility is a huge - often overlooked - feature in modern web applications. Angular Material components all implement ARIA features whenever possible. And for usage scenarios where the ARIA attributes are not explicitly provided and cannot be inferred, then Angular Material will provide details console warnings alerting the developer.

Let’s use the Angular Material Theming service to change the background, primary, accent, and warning colors used within the entire application. These will be configured at startup using the $mdThemeProvider.

Let’s also resolve the two ARIA warnings shown in console. These originate from icon buttons where the ARIA label cannot be inferred. So let’s add a static aria-label and a dynamic, interpolated aria-label to those buttons.