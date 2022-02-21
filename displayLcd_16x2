#include <LiquidCrystal.h>
 
LiquidCrystal lcd(12, 11, 5, 4, 3, 2);//DEF PIN
 
void setup()
{
  lcd.begin(16, 2);// Display INIT + SET COLs and ROWs
}
 
void loop()
{

  lcd.clear();
  
  lcd.setCursor(3, 0);//SET cursor at COL 3 ROW 0
  lcd.print("MEU DISPLAY");//SEND text to CURSOR position
  lcd.setCursor(3, 1); // SET cursor at COL 3 ROW 1
  lcd.print("CAIO SILVA");//SEND text to CURSOR position
  delay(5000);//Wait for 5 seconds
   
  //Scroll TEXT to LEFT then RIGHT
  for (int posicao = 0; posicao < 3; posicao++)
  {
    lcd.scrollDisplayLeft();
    delay(300);
  }
  for (int posicao = 0; posicao < 5; posicao++)
  {
    lcd.scrollDisplayRight();
    delay(300);
  }

}
