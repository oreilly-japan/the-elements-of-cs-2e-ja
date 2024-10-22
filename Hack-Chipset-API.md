# Hackチップセット API

| API | 説明 |
|-----|------|
| `Add16(a = , b = , out = )` | 2つの16ビットの2の補数値を加算する |
| `ALU(x = , y = , zx = , nx = , zy = , ny = , f = , no = , out = , zr = , ng = )` | Hack の ALU |
| `And(a = , b = , out = )` | And ゲート |
| `And16(a = , b = , out = )` | 16ビット And |
| `ARegister(in = , load = , out = )` | アドレスレジスタ（ビルトイン） |
| `Bit(in = , load = , out = )` | 1ビットレジスタ |
| `CPU(inM = , instruction = , reset = , outM = , writeM = , addressM = , pc = )` | Hack CPU |
| `DFF(in = , out = )` | Dフリップフロップゲート（ビルトイン） |
| `DMux(in = , sel = , a = , b = )` | 入力を2つの出力のうちひとつにルーティングする |
| `DMux4Way(in = , sel = , a = , b = , c = , d = )` | 入力を4つの出力のうちひとつにルーティングする |
| `DMux8Way(in = , sel = , a = , b = , c = , d = , e = , f = , g = , h = )` | 入力を8つの出力のうちひとつにルーティングする |
| `DRegister(in = , load = , out = )` | データレジスタ（ビルトイン） |
| `FullAdder(a = , b = , c = , sum = , carry = )` | 3ビットの足し算 |
| `HalfAdder(a = , b = , sum = , carry = )` | 2ビットの足し算 |
| `Inc16(in = , out = )` | outをin+1に設定する |
| `Keyboard(out = )` | キーボードのメモリマップ（ビルトイン） |
| `Memory(in = , load = , address = , out = )` | Hackプラットフォームのデータメモリ RAM |
| `Mux(a = , b = , sel = , out = )` | 2つの入力から選択する |
| `Mux16(a = , b = , sel = , out = )` | 2つの16ビット入力から選択する |
| `Mux4Way16(a = , b = , c = , d = , sel = , out = )` | 4つの16ビット入力から選択する |
| `Mux8Way16(a = , b = , c = , d = , e = , f = , g = , h = , sel = , out = )` | 8つの16ビット入力から選択する |
| `Nand(a = , b = , out = )` | Nand ゲート（ビルトイン） |
| `Not(in = , out = )` | Not ゲート |
| `Not16(in = , out = )` | 16ビット Not |
| `Or(a = , b = , out = )` | Or ゲート |
| `Or16(a = , b = , out = )` | 16ビット Or |
| `Or8Way(in = , out = )` | 8入力 Or |
| `PC(in = , load = , inc = , reset = , out = )` | プログラムカウンタ |
| `RAM8(in = , load = , address = , out = )` | 8ワード RAM |
| `RAM64(in = , load = , address = , out = )` | 64ワード RAM |
| `RAM512(in = , load = , address = , out = )` | 512ワード RAM |
| `RAM4K(in = , load = , address = , out = )` | 4Kワード RAM |
| `RAM16K(in = , load = , address = , out = )` | 16Kワード RAM |
| `Register(in = , load = , out = )` | 16ビットレジスタ |
| `ROM32K(address = , out = )` | Hackプラットフォームの命令メモリ（ROM、ビルトイン） |
| `Screen(in = , load = , address = , out = )` | 画面のメモリマップ（ビルトイン） |
| `Xor(a = , b = , out = )` | Xor ゲート |
