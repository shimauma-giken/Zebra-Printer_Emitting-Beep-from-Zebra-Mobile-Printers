# ゼブラモバイルプリンタからビープ音を鳴らす方法

</br>


置き場所がわからなくなったモバイルプリンタから、特定通知音を出力させたい。わかります。本スレッドではモバイルプリンタからピング音を出力するコマンドをご紹介します。
</br>



### 構文

! U BEEP [Duration]<CR><LF> END
</br>

### パラメータ解説

|Parameter| Description| Valid Range|
|:-:|:-:|:-:|
| Duration |  1単位で1/8秒間ビープを鳴らす | 0 - 65535
</br>

### 例文

ビープ音0.5秒を3回発信する。

    ! U 
    BEEP 4 
    BEEP 4 
    BEEP 4 
    END

</br>
</br>

完成です！