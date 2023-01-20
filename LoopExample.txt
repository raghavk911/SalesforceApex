public class LoopExample {
    public void run(){
        integer i=1;  
        while(i<=10){  
            System.debug('In While:: '+i);  
        	i++;  
        } 
    }
    
    public void execute(){
        integer i=1;    
        do{    
            System.debug('In Do-While:: '+i);    
        i++;    
        }while(i<=10);       
    }
}