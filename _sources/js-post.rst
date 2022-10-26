Post Test
-----------------------------------------------------

Please answer
the following problems to the best of your ability without any
outside help. You can stop working on a problem after you worked
on it for about five minutes without solving it.

Problems
==============
.. activecode:: lccv1
   :language: java
   :autograde: unittest

   Finish writing the code to swap the values in x and y (so that x ends up with y's initial value and y ends up with x's initial value).
   ~~~~
   public class Test1
   {
      public static void main(String[] args)
      {
          int x = 3;
          int y = 5;
          int temp = 0;

          // swap the Values

          // print the Values
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
            int x = 3;
            int y = 5;
            int temp = 0;
            String expect = "5\n1\3";
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
