Post Test
-----------------------------------------------------

Please answer
the following problems to the best of your ability without any
outside help. You can stop working on a problem after you worked
on it for about five minutes without solving it.

Problems
==============

.. activecode:: js-swap-ac
   :language: java
   :autograde: unittest

   Finish writing the code to swap the values in a and b (so that a ends up with b's initial value and b ends up with a's initial value).
   ~~~~
   public class Test1
   {
      public static void main(String[] args)
      {
          int x = 6;
          int y = 2;
          int temp = 0;

          // print the values
          System.out.println(x);
          System.out.println(y);

          // swap the values

          // print the values
          System.out.println(x);
          System.out.println(y);
      }
   }
   ====
   // Test Code
    import static org.junit.Assert.*;
    import org.junit.After;
    import org.junit.Before;
    import org.junit.Test;

    import java.io.*;

    public class RunestoneTests extends CodeTestHelper
    {
        @Test
        public void test1()
        {
            int a = 6;
            int b = 2;
            int temp = 0;
            String expect = "6\n2\n2\n6\n";
            String output = getMethodOutput("main");
            boolean passed = getResults(expect, output, "Expected output from main", true);
            assertTrue(passed);
        }
    }


Feedback
==================================

.. shortanswer:: js-posttest-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.

Thank You
============================
Thank you for taking part in this study!  We appreciate your time on this.
