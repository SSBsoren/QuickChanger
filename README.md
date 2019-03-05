# QuickChanger
To switch background color.
-----------------------------------------------------------------------------------------------------------
1.activity.xml
---------------
     >RelativeLayout
     >RadioGroup
     >Radio Buttons
2.MainActivity.java
-------------------
  1.switch (checkedID){
                    case R.id.radio_btnB:
                        layout.setBackgroundColor(Color.parseColor("#74B9FF"));
                        break;
                    case R.id.radio_btnG:
                        layout.setBackgroundColor(Color.parseColor("#45CE30"));
                        break;
                    case R.id.radio_btnR:
                        layout.setBackgroundColor(Color.parseColor("#FF3E40"));
                        break;
