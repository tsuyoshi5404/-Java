# -Java

public class main {
  public static void main (String[] args) {
    System.out.print("何段のピラミッドをつくる？>");
    int num = new java.util.Scanner(System.in).nextInt();

    //何行か
    for(int i = 0; i < num; i++) {
    //何列
      for(int j = 0; j < num + 1; j++) {
    //空白何個作る
        if(j < num - 1 - i) {
          System.out.print(' ');
        } else {
        System.out.print('*');
      }
    }
    //列の出力が終われば改行
    System.out.println();
  }
}
