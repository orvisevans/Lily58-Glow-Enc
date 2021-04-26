# Lily58 × qtkb Glow + Rotary Encoders

This is still very much under active development. I've ordered the pcb and parts and am waiting for them to arrive. Since then, I've found some incompatibilities between the design and product list. I've not yet tested in the real world or worked out there bugs.

Lily58 is 6×4+4keys column-staggered split keyboard.
This fork adds an encoder to the key below the controller.

I got this board manufactured by JLCPCB. Just upload the file called gerber.zip to their quote tool, choose how many (5 is minimum), choose your color, (default options are fine) and order! Mine were $8.40 for a set of 5 and $9.03 shipping in July 2020.

If you don't want underglow, bridge dio from the first underglow led (L34) to the first led of the keys (L1) and update the code accordingly.

This picture is from the original Lily58 Glow. Pictures of this project are forthcoming.
![Lily in the nighttime](https://i.imgur.com/uvap4Nt.jpg)

## PCB Front

![PCB Front](img/PCB-Front.png)

## PCB Back

![PCB Back](img/PCB-Back.png)

# Parts

| Part Name                    | Quantity | Link                                                                                                                                                                                                                                                                                          | Price/Unit | Total    |
| ---------------------------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | -------- |
| Lily58L PCB                  | 2        | JLCPCB                                                                                                                                                                                                                                                                                        | \$8.72     | \$17.43  |
| Lily58L Case                 | 1        | Using 2 more circuit boards as the bottom. No other case for now.                                                                                                                                                                                                                             | \$0.00     | \$0.00   |
| Pro Micro                    | 2        | https://www.aliexpress.com/item/32888212119.html?spm=a2g0o.productlist.0.0.30d25a53xh6DaX&algo_pvid=9e5fb73d-c3e5-475f-bda1-b4666011fa38&algo_expid=9e5fb73d-c3e5-475f-bda1-b4666011fa38-8&btsid=0ab6f82215936295153445783e35b6&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_     | \$5.59     | \$11.17  |
| Micro USB Cable              | 2        | --                                                                                                                                                                                                                                                                                            | \$0.00     | \$0.00   |
| OLED module                  | 2        | https://www.aliexpress.com/item/32861875681.html?spm=a2g0o.productlist.0.0.835aa9ccjrnsdV&algo_pvid=7def10f1-db5f-4a13-951c-5bf7341c096e&algo_expid=7def10f1-db5f-4a13-951c-5bf7341c096e-0&btsid=0ab6d69f15936287684868637e6e79&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_     | \$1.96     | \$3.92   |
| Rotary Encoder               | 2        | https://www.aliexpress.com/item/32322425597.html?spm=a2g0o.productlist.0.0.6102314aqRHfGU&algo_pvid=281c4dc1-9caa-459f-8650-fbba7e4bec4d&algo_expid=281c4dc1-9caa-459f-8650-fbba7e4bec4d-9&btsid=0ab6d70515937408315558637e0bf2&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_     | \$1.68     | \$3.35   |
| Knob                         | 2        | --                                                                                                                                                                                                                                                                                            |            | \$0.00   |
| Key switch (MX)              | 58       | https://www.aliexpress.com/item/32973993662.html?spm=a2g0o.productlist.0.0.6fdb14ebdXgCiL&algo_pvid=dc98baa5-021b-42b9-806a-ef67fe903a97&algo_expid=dc98baa5-021b-42b9-806a-ef67fe903a97-10&btsid=0ab6d69515936249739887508eaca4&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_    | \$0.29     | \$16.99  |
| Kailh switch socket          | 58       | https://www.aliexpress.com/item/10000252734106.html?spm=a2g0o.productlist.0.0.6b9a1faaM3DsBf&algo_pvid=aa995bed-9941-44f5-8e5d-accedfc3bf1e&algo_expid=aa995bed-9941-44f5-8e5d-accedfc3bf1e-10&btsid=0be3743615936252288275769e1733&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_ | \$0.22     | \$12.90  |
| SK6812 Mini LEDs           | 60       | https://www.aliexpress.com/item/33019583218.html?spm=a2g0s.9042311.0.0.12a84c4dEvt2eo   | \$0.18     | \$10.71  |
| SK6812 Mini LEDs             | 12       | Use the above link                                                                                                                                                                                                                                                  |            | \$0.00   |
| Diodes 1N4148 (Through-hole) | 58       | https://www.aliexpress.com/item/1934432186.html?spm=a2g0o.productlist.0.0.43075a93S1HiAy&algo_pvid=2a96b464-fcb2-4d4d-9db0-5325780cc08b&algo_expid=2a96b464-fcb2-4d4d-9db0-5325780cc08b-2&btsid=0ab6f82415937472454356384e6daf&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_      | \$0.04     | \$2.48   |
| TRRS Jack                    | 2        | https://www.aliexpress.com/item/33029465106.html?spm=a2g0o.productlist.0.0.4c934e0cJHeHoK&algo_pvid=eae4b36e-738c-4df6-8e73-ad7bf5885647&algo_expid=eae4b36e-738c-4df6-8e73-ad7bf5885647-0&btsid=0ab6fab215936264228847161e1394&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_     | \$1.63     | \$3.26   |
| TRRS Cable                   | 1        | https://www.aliexpress.com/item/33000197351.html?spm=a2g0o.productlist.0.0.21a2246ecsIFwV&algo_pvid=fd7c3341-82d4-4c30-813e-1d52c9431132&algo_expid=fd7c3341-82d4-4c30-813e-1d52c9431132-3&btsid=0ab6fab215936268107442907e1395&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_     | \$1.79     | \$1.79   |
| Tactile switch               | 0        | Needed but not sourced.                                                                                                                                                                                                                                                                       |            | \$0.00   |
| Key Caps                     | 58       | https://www.aliexpress.com/item/32744591039.html?spm=a2g0o.cart.0.0.1fff3c00zqG7Sv&mp=1                                                                                                                                                                                                       | \$0.44     | \$25.5   |
| M2 Standoffs                 | 14       | https://www.aliexpress.com/item/32839434178.html?spm=a2g0o.productlist.0.0.55a049d0Wpvk4j&algo_pvid=b7593b96-f169-4b42-9f04-20554ae42bde&algo_expid=b7593b96-f169-4b42-9f04-20554ae42bde-19&btsid=0ab6f83115936383891028466e7acb&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_    | \$0.57     | \$7.99   |
| M2 Screws                    | 28       | https://www.aliexpress.com/item/32730208891.html?spm=2114.12010612.8148356.21.445e15ccXDyc9g                                                                                                                                                                                                  | \$0.21     | \$5.74   |
|                              |          |                                                                                                                                                                                                                                                                                               | Total:     | \$115.80 |
