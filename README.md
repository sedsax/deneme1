# deneme1

https://developer.android.com/jetpack/compose/tutorial

=> A simple chat screen efficiently showing a list of expandable & animated messages containing an image and texts

1: Composable functions
      - Add a text element
      - Define a composable function
      - Preview your function in Android Studio

2: Layouts
      - Add multiple texts
      - Using a Column
      - Add an image element
      - Configure your layout

3: Material Design
      - Use Material Design
      - Color
      - Typography
      - Shape
      - Enable dark theme

4: Lists and animations
      - Create a list of messages
      - Animate messages while expanding

=> Jetpack Compose ile XML ve Layout olmadan, düzenlenişi daha kolay bir arayüz tasarladık. Kullanıcıyı temsil eden bir Image ve kullanıcının adıyla mesajını temsil eden iki tane Text tanımladık. 

=> Bu küçük projeyi uygularken neler öğrendim ve ne gibi notlar aldım? Jetpack Compose' un UI kullanımlarında bilmediğim kavramları ve sonunda Github ile ilgili kavramların bazılarını, Android Studio ile Github bağlantısını sağlamayı öğrendim. 

=> Kullanılan ve import edilen tasarım bileşenleri:
  - modifiers
  - MaterialTheme (MaterialTheme.colors, MaterialTheme.typography, MaterialTheme.shapes)
  - LazyColumn
  
=> Projede eksik olan ve çalıştırılamayan kısımlar:
  - Örnekte uygulanmış olan koyu renkli tema bende çalışmadı ve araştırmalarıma rağmen henüz koyu renk temayı ekleyemedim.
  
/*
                                            import android.content.res.Configuration

                                            @Preview(name = "Light Mode")
                                            @Preview(
                                                uiMode = Configuration.UI_MODE_NIGHT_YES,
                                                showBackground = true,
                                                name = "Dark Mode"
                                            )
                                            @Composable
                                            fun PreviewMessageCard() {
                                               ComposeTutorialTheme {
                                                Surface {
                                                  MessageCard(
                                                    msg = Message("Colleague", "Hey, take a look at Jetpack Compose, it's great!")
                                                  )
                                                }
                                               }
                                            }  
 Yukarıdaki gibi bir ekleme yapmak gerekiyordu ben de aynı şekilde yaptım, herhangi bir hata da almadım ancak tema rengi değişmedi. Daha sonra tekrar bakacağım.
*/
  
