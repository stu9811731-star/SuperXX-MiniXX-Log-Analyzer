# XXFueL V4.4.4

Browser-based MiniXX fuel correction, before-after Log comparison, ignition-angle and manifold-pressure analysis, and local fuel-map screenshot recognition.

V4.4.4 gives every public page the same XXFueL header structure while retaining a distinct page title and purpose line. Browser-tab titles now consistently use the XXFueL brand, and an automated test prevents future pages from drifting away from the shared header.

V4.4.3 adds an original MiniXX learning center with eight practical articles, an About page, clearer site navigation, page-specific descriptions and canonical URLs, plus `robots.txt` and `sitemap.xml`. The analyzer calculations and conservative safety gates remain the validated V4.4.2 behavior.

V4.4.2 adds a base-fuel percentage control. The result view can now calculate the final fuel value with `global fuel × base fuel ÷ 100`, while keeping the default at 100% when the control is not changed. The slider and numeric input stay synchronized and update the displayed result immediately.

The release retains the improved local fuel-map screenshot recognition from V4.4.1. Low-resolution screenshots are enlarged before OCR; values with a dropped decimal point such as `875` are restored to `87.5`, and a missing leading digit such as `17.1` can be restored to `117.1` only when the surrounding table values support that repair. Automatically repaired cells are shown in yellow for manual confirmation.

The release retains Apple and Android Log detection, Fuel_CL mismatch protection, conservative safety gates, 0.8-step fuel suggestions, before/after comparison, and the ignition/manifold-pressure result page. Logs and screenshots remain on the user's device.
