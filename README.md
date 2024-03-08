# Taraki
public class SelfMotivation {
    public static void main(String[] args) {
        displayMotivation();
    }
    
    public static void displayMotivation() {
        String[] messages = {
            "Believe in yourself and all that you are. Know that there is something inside you that is greater than any obstacle.",
            "Success is not final, failure is not fatal: It is the courage to continue that counts.",
            "Your limitation—it's only your imagination.",
            "Push yourself, because no one else is going to do it for you.",
            "Great things never come from comfort zones.",
            "Dream it. Wish it. Do it."
        };
        
        int randomIndex = (int) (Math.random() * messages.length);
        System.out.println("Motivational message of the day:");
        System.out.println(messages[randomIndex]);
    }
}
