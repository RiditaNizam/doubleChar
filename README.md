public String doubleChar(String str) {
  
  String answerString = "";
  
  for(int i = 0; i < str.length(); i++){
    answerString+= str.substring(i,i+1) + str.substring(i, i+1);
  }
  
  return answerString;
  
}
