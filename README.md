# Java-101
I'm learning Java. https://github.com/SciBorgs/SciGuides/blob/main/projects/intro-to-programming/README.md 

Pratice Problems
1. public class Main{
    public static int counterOccurences (var arr, int n){
      int n = n
     for (int num : arr ) {
       if (num == n){
        }
    }
    return num
     }
   }

2.  public static int[] reverseArray (int[] arr){
        int[] reversedArray = new int[arr.length];
    for (int x = 0; x < arr.length; x++){
       reversedArray[x] = arr[arr.length]
    }
    return reversedArray
} 

3. public static double[][] sumGrid(double[][] grid){
    double sum = 0;   
for (double x = 0; x < grid.length; x++){
        for (double y = 0; y < grid[x].length; y++){
            sum += grid[x][y];
       }
   }
    return sum;
 }

4. public static void fib (String[] args){
    int sum = 0;
   int [] fib = {0, 1, 1, 2, 3, 5, 8, 13, 21, 34}
   for (int n : fib){
        sum = sum + n;
   }
return sum
 }

                                                            Java 102

Center of Mass:
    public static Point centerOfMass (Point[] points);
        double x, y;
        public Point (double x, double y){
        this.x = x;
        this.y = y;
        }
    public Point centerOfMass(Point[] points){
        double sumX = 0;
        double sumY = 0;
        for (int i = 0; i<points.length, i++){
        sumX += p.x;
        sumY += p.y;
        }
        return new Point
}

Angle: 
    public class Point{
        private double x,y; 
        public Point (double x, double y){
            this.x = x;
            this.y = y;
        }
        public double angle(){
            return Math.toDegrees(Math.radians2(y,x));
        }
    }

Diagonal: 
    private final ArrayList< T> grid;
    public dinal int sideLength;
    public Grid(int sideLength, T defaultVal){
        this.sideLength = sideLength;
        this.grid = new ArrayList <T> (sideLength);
        for (int i = 0; i < sideLength; i++){
            grid.add(new ArrayList<>(sideLength));
            for (int j = 0; j < sideLength; j++){
                grid.get(i).add(defaultVall);
        }
        }
    public T get(int row, int col){
        return grid.get(row) .get(col);
    }
    public void set(int row, int col, T val){
        grid.get(row) .set(col, val);
    }
    @Override 
    public String toString(){
        String str = "";
        for (ArrayList<T> row: grid){
            for(T element:row){
                str+=element +"";
            }
            str+="\n";
        }
        return str;
    }
}

returnAll: 
    public static void returnAll(LibraryItem[] items){
        for(LibraryItem item : items){
        item.returnItem(); 
        System.out.printIn(item.title + "has been returned.");
        }
    
    public static void main(String[] args){
        LibraryItem book1 = new LibraryItem("Rabbit", B001);
        LibraryItem dvd1 = new LibraryItem("Cat", D001);
        book1.isCheckedOut = true;
        dvd1.isCheckedOut = true;

        LibraryItem[] items = {book1, dvd1};
    }
        return All(items);
}

availableItems: 
    public class LibraryItem{}
        public static ArrayList<LibraryItem> available Items(LibraryItem[] items){
        boolean is CheckedOut = false;
        public LibraryItem(String title, String itemId){
            this.title = title;
            this.itemId = itemId;
        }
        public boolean available(){
            return !isCheckedOut;
    }
        public void returnItem(){
            isCheckedOut = false;
    }
        public void checkedOut(){
        isCheckedOut = true;
        }
    }
