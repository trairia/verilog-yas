verilog-yas
==========
verilog 記述のための yasnippet.  
(snippets for verilog coding)

使い方(How to)
----------
yasnippet の変数 'yas/root-directory' が示すパス
に snippets/verilog-mode を放り込みます。

yasnippet 自体の設定は
[yasnippet](https://github.com/capitaomorte/yasnippet)
を参照して下さい。

Snippets
----------
+ module
    
    module (/*AUTOARG*/);
  
    endmodule //

+ always

    always @(posedge clk or negedge xrst) begin
	    
	end
	

+ if

	if (condition) begin
	
	end


今後
----------
いろいろ成長させて行きます。
