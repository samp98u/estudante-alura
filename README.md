@@ -0,0 +1,16 @@
: raiz {
    --branco- principal :  #FFFFFF ;
    --cinza-secundario :  # C0C0C0 ;
    --botao-azul :  # 167BF7 ;
    --cor-de-fundo :  # 00030C ;
}

corpo {
    cor de fundo :  var ( -cor-de-fundo );
    cor :  var ( --branco-principal );
}

* {
    margem :  0 ;
    preenchimento :  0 ;
}
