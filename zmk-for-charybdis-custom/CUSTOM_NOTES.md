# Charybdis ZMK Customization Notes

- Lowered PMW3610 CPI:
  - `CONFIG_PMW3610_CPI=200`
  - `CONFIG_PMW3610_CPI_DIVIDOR=2`
  (edit `config/boards/shields/charybdis/charybdis_right.conf`)

- Added precision mode layer (layer_3) with `trackball-bindings = <&tmv_fine>;`
  - Hold `Right Alt` to activate precision mode (`&lt 3 RIGHT_ALT`) from base layer.

- Scroll layer (layer_1) remains `trackball-bindings = <&tsl>;`
  - Added key scroll left/right on layer_1 near the Up key: `&msc SCRL_LEFT` and `&msc SCRL_RIGHT`.

