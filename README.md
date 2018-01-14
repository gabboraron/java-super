You can define any arguments you need for your constructor, but it is necessary to call one constructor of the super class as the first line of your own constructor. This can be done using super() or super(arguments).

    public class CMainCharacter extends CAnimatedSprite {

        public CMainCharacter() {
            super("your pFn value here", 0, 0);
            //do whatever you want to do in your constructor here
        }

        public CMainCharacter(String pFn, int pWidth, int pHeight) {
            super(pFn, pWidth, pHeight);
            //do whatever you want to do in your constructor here
        }

    }

source: https://stackoverflow.com/questions/2056097/java-extending-class-with-the-constructor-of-main-class-has-parameter
