// ignore: import_of_legacy_library_into_null_safe
import 'package:carousel_pro/carousel_pro.dart';
import 'package:flutter/material.dart';

void main(){
  runApp(
      MaterialApp(
      home: Homepage(
      ),
    )
  );
    }
class Homepage extends StatefulWidget {
  @override
  _HomepageState createState() => _HomepageState();
}

class _HomepageState extends State<Homepage> {
  @override
  Widget build(BuildContext context) {
   Widget imageCarousel  = new Container( // ignore: unused_local_variable
     height: 200.0,
     child : new Carousel(
       boxFit: BoxFit.cover,
       images: [
         AssetImage('images-20210612T034447Z-001/images/c1.jpg'),
         AssetImage('images-20210612T034447Z-001/images/m1.jpeg'),
         AssetImage('images-20210612T034447Z-001/images/m2.jpg'),
         AssetImage('images-20210612T034447Z-001/images/w1.jpeg'),
         AssetImage('images-20210612T034447Z-001/images/w3.jpeg'),
         AssetImage('images-20210612T034447Z-001/images/w4.jpeg'),
       ],
       autoplay: false,
       animationCurve: Curves.fastOutSlowIn,
       animationDuration: Duration(milliseconds: 1000),
       indicatorBgPadding: 6.0 ,


     ),
   );
    return Scaffold(
      appBar: new AppBar(
        elevation: 0.0,
        backgroundColor: Colors.red,
          title: Text('shoppApp'),
           actions:<Widget> [
             new IconButton(icon: Icon(Icons.search,color: Colors.white,),onPressed:(){}),
             new IconButton(icon: Icon(Icons.shopping_cart,color: Colors.white,),onPressed:(){})


        ],
        ),
          drawer: new Drawer(
        child: new ListView(
        children:<Widget> [
          new UserAccountsDrawerHeader(
              accountName: Text('Yethukichu'),
              accountEmail: Text('yethukichu552gmail.com'),
              currentAccountPicture: GestureDetector(
                child: CircleAvatar(
                  backgroundColor: Colors.grey,
                  child:Icon(Icons.person,color: Colors.white,)
                ),
          ),
            decoration:new BoxDecoration(
              color: Colors.red
            )

          ),
          //body
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('HomePage'),
              leading: Icon(Icons.home,color:Colors.black),
            ),
          ),
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('MyAccount'),
              leading: Icon(Icons.person,color:Colors.black),
            ),
          ),
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('MyOrders'),
              leading: Icon(Icons.shopping_basket,color:Colors.black),
            ),
          ),
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('categories'),
              leading: Icon(Icons.dashboard,color:Colors.black),
            ),
          ),
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('Favorites'),
              leading: Icon(Icons.favorite ,color:Colors.red ),
            ),
          ),
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('settings'),
              leading: Icon(Icons.settings,color:Colors.lightBlue),
            ),
          ),
          InkWell(
            onTap: (){},
            child: ListTile(
              title: Text ('about'),
              leading: Icon(Icons.help,color:Colors.green),
            ),
          ),





        ],


    ),

    ),
     body: new ListView(
       children:<Widget>[
         imageCarousel
       ],
     ),
    );
  }
}
