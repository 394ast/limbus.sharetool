//既知の不具合　ランレングス圧縮に36進数を使っているため36種類目の人格が登場するとバグが発生 
//同期化段階は1桁を想定しているため同期化10段階が実装されるとバグが発生
//レベルは圧縮に16進数を使っているため最大レベルが256を超えるとバグが発生

//新規人格E.G.O実装時の手引き
//5種のimageStateにそれぞれjpgをアップロードする
//groupSettingsのcountを書き換える//indexとtopの両方とも忘れずに書き換える
//レベル上限更新時は3か所それぞれindexとtopを書き換える
