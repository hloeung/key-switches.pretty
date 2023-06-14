# Key Switches

This is a [KiCad](https://www.kicad.org/) footprint library of mechanical keyboard switches.

> A part of [ErgoSNM keyboard](https://github.com/ziteh/ergo-snm-keyboard) project.  

## Compatibility Table

| Footprint                                   |     Cherry MX      | Cherry MX Low Profile |   TTC KS32   |   Kailh Choc V1    |   Kailh Choc V2    | Gateron Low Profile |     THT *(1)*      |      Hot-Swap      | Note         |
| :------------------------------------------ | :----------------: | :-------------------: | :----------: | :----------------: | :----------------: | :-----------------: | :----------------: | :----------------: | :----------- |
| SW_MX_HotSwap_THT                           | :white_check_mark: |                       |              |                    |                    |                     | :white_check_mark: | :white_check_mark: |              |
| SW_MX_HotSwap_THT_double                    | :white_check_mark: |                       |              |                    |                    |                     | :white_check_mark: | :white_check_mark: | Double sided |
| SW_MX_HotSwap_THT_double_alt1               | :white_check_mark: |                       |              |                    |                    |                     | :white_check_mark: | :white_check_mark: | Double sided |
| SW_MX_HotSwap_THT_double_alt2               | :white_check_mark: |                       |              |                    |                    |                     | :white_check_mark: | :white_check_mark: | Double sided |
| SW_MX_HotSwap_PTH                           | :white_check_mark: |                       |              |                    |                    |                     |    :bulb: *(2)*    | :white_check_mark: |              |
| SW_MX_HotSwap_PTH_double                    | :white_check_mark: |                       |              |                    |                    |                     |    :bulb: *(2)*    | :white_check_mark: | Double sided |
| SW_MX_LowProfile_THT                        |                    |  :white_check_mark:   | :bulb: *(3)* |                    |                    |                     | :white_check_mark: |                    |              |
| SW_Gateron_LowProfile_HotSwap_THT           |                    |                       |              |                    |                    | :white_check_mark:  | :white_check_mark: | :white_check_mark: |              |
| SW_Kailh_Choc_V1_THT                        |                    |                       |              | :white_check_mark: |                    |                     | :white_check_mark: |                    |              |
| SW_Kailh_Choc_V2_THT                        |                    |                       |              |                    | :white_check_mark: |                     | :white_check_mark: |                    |              |
| SW_Kailh_Choc_V1V2_THT_Hybrid               |                    |                       |              |    :bulb: *(4)*    | :white_check_mark: |                     | :white_check_mark: |                    | Hybrid       |
| SW_MX_LowProfile_Kailh_Choc_V1V2_THT_Hybrid |                    |  :white_check_mark:   | :bulb: *(3)* |    :bulb: *(4)*    |    :bulb: *(5)*    |                     | :white_check_mark: |                    | Hybrid       |

1. **THT** means through-hole soldering.
2. **PTH** means the holes of Hot-Swap socket are plated, the switches can be soldered without socket.
3. *TTC KS32* and *Cherry MX Low Profile* are very similar, basically compatible.
4. The center fix pin of *Choc V1* is smaller than *Choc V2*, however *Choc V1* has two additional fix pins ensuring its stability.
5. The center fix pin of *Choc V2* is smaller than *Cherry MX Low Profile*, *Choc V2* may not be securely fastened.

## Footprints List

| Footprint                                   | Description                                                                                                                                                                                                    |               Preview                |
| :------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------: |
| SW_MX_HotSwap_THT                           | Cherry MX style mechanical keyboard switch, Kailh/Gateron hot-swap socket and through-hole soldering, single-sided mounting.                                                                                   | ![](https://i.imgur.com/gQgppii.jpg) |
| SW_MX_HotSwap_THT_double                    | Cherry MX style mechanical keyboard switch, Kailh/Gateron hot-swap socket and through-hole soldering, double-sided mounting.                                                                                   | ![](https://i.imgur.com/Se1CHMa.jpg) |
| SW_MX_HotSwap_THT_double_alt1               | Cherry MX style mechanical keyboard switch, Kailh/Gateron hot-swap socket and through-hole soldering, double-sided mounting. An alternative to "SW_MX_HotSwap_THT_double".                                     | ![](https://i.imgur.com/pFtTYBV.jpg) |
| SW_MX_HotSwap_THT_double_alt2               | Cherry MX style mechanical keyboard switch, Kailh/Gateron hot-swap socket and through-hole soldering, double-sided mounting. An alternative to "SW_MX_HotSwap_THT_double".                                     | ![](https://i.imgur.com/wPHmvjv.jpg) |
| SW_MX_HotSwap_PHT                           | Cherry MX style mechanical keyboard switch, Kailh/Gateron hot-swap socket and through-hole soldering, the hole of the socket is plated, single-sided mounting.                                                 | ![](https://i.imgur.com/ySLGt4U.jpg) |
| SW_MX_HotSwap_PHT_double                    | Cherry MX style mechanical keyboard switch, through-hole soldering and Kailh/Gateron hot-swap socket, the hole of the socket is plated, double-sided mounting.                                                 | ![](https://i.imgur.com/UiA5tTy.jpg) |
| SW_MX_LowProfile_THT                        | Cherry MX Low Profile mechanical keyboard switch, through-hole soldering, single-sided mounting.                                                                                                               | ![](https://i.imgur.com/prosQX5.jpg) |
| SW_Gateron_LowProfile_HotSwap_THT           | Gateron Low Profile style mechanical keyboard switch, Gateron Low Profile hot-swap socket and through-hole soldering, single-sided mounting. Gateron Low Profile and Cherry MX Low Profile are NOT compatible. | ![](https://i.imgur.com/5gt9NUf.jpg) |
| SW_Kailh_Choc_V1_THT                        | Kailh Choc V1 (PG1350) low profile mechanical keyboard switch, through-hole soldering, single-sided mounting.                                                                                                  | ![](https://i.imgur.com/sl01MNS.jpg) |
| SW_Kailh_Choc_V2_THT                        | Kailh Choc V2 (PG1353) low profile mechanical keyboard switch, through-hole soldering, single-sided mounting.                                                                                                  | ![](https://i.imgur.com/mK65Vrx.jpg) |
| SW_Kailh_Choc_V1V2_THT_Hybrid               | Compatible with Kailh Choc V1 (PG1350) and Choc V2 (PG1353) low profile mechanical keyboard switch, through-hole soldering, single-sided mounting.                                                             | ![](https://i.imgur.com/DStr5La.jpg) |
| SW_MX_LowProfile_Kailh_Choc_V1V2_THT_Hybrid | Compatible with Kailh Choc V1 (PG1350) and Choc V2 (PG1353) low profile mechanical keyboard switch, through-hole soldering, single-sided mounting.                                                             | ![](https://i.imgur.com/9mmCyuX.jpg) |


> Most keyboard switches are spaced by 19.05 mm (3/4 inch) from center-to-center.  
