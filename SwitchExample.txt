public class SwitchExample {
// Enter Shirt Size
    public void run(){
	integer i = 44;
        switch on i { 
               when 40 {
                   System.debug('Your size is M');
               }       
               when 42 {
                   System.debug('Your size is L');
               }
               when 44 {
                   System.debug('Your size is XL');
               }
               when 48 {
                   System.debug('Your size is XXL');
               }
               when else {
                   System.debug('Enter appropriate size');
               }
        }
    }
}