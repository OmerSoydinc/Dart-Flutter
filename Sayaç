import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      debugShowCheckedModeBanner:false,
      home:Scaffold(
        appBar:AppBar(
          title:Text("Sayaç Uygulamam :)"),
        ),
        body:Deneme(),
      ),
    ),
  );
}

class Deneme extends StatefulWidget{
  @override
  _DenemeState createState() => _DenemeState();
}

class _DenemeState extends State<Deneme>{
  int sayac=0;
  @override
  Widget build(BuildContext context){
    return Column(
      mainAxisAlignment:MainAxisAlignment.center,
      crossAxisAlignment:CrossAxisAlignment.center,
      children:[
        Row(
          mainAxisAlignment:MainAxisAlignment.center,
          children:[
            ElevatedButton(
              style:ElevatedButton.styleFrom(
                fixedSize: Size(30,50),primary:Colors.green),
              child:Text(
                "+",
                style:TextStyle(fontSize:35),
              ),
              onPressed:(){
                setState((){
                  sayac++;
                }
                );

              },
              ),



                ElevatedButton(
                    style:ElevatedButton.styleFrom(
                      fixedSize:Size(30,50),primary:Colors.red),
                  child:Text(
                    "-",
                  style:TextStyle(fontSize:35),
                  ),
                  onPressed:() {
                      setState((){
                        sayac--;
                      }
                      );
                      },

                ),//amk yerine ; yazmışım
          ],

                  ),


     SizedBox(height:20,),
     Text("Sayaç : $sayac",
        style:TextStyle(fontSize:30),

  ),
    ],
    );
  }
}
