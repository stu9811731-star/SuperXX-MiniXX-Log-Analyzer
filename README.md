# XXFueL V4.4.1

Browser-based MiniXX fuel correction, before-after Log comparison, ignition-angle and manifold-pressure analysis, and local fuel-map screenshot recognition.

V4.4.1 improves local fuel-map screenshot recognition. Low-resolution screenshots are enlarged before OCR; values with a dropped decimal point such as `875` are restored to `87.5`, and a missing leading digit such as `17.1` can be restored to `117.1` only when the surrounding table values support that repair. Automatically repaired cells are shown in yellow for manual confirmation.

The release retains Apple and Android Log detection, Fuel_CL mismatch protection, conservative safety gates, 0.8-step fuel suggestions, before/after comparison, and the ignition/manifold-pressure result page. Logs and screenshots remain on the user's device.
