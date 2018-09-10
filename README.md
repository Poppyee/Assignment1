# Assignment1

package Problem1;

public interface Specification {

	/*
	  Elements: 
	  Structure: 
	  Domain: alphanumeric characters (a-z, 0-9)
	  
	 constructors
	 
	 AlphaNumericStack();
	 PRE-
	 POST - A new AlphaNumericStack-object has been made and contains the empty stack
	 
	 AlphaNumericStack(AlphaNumericStack source);
	 PRE-
	 POST - A new AlphaNumericStack-object has been made and contains a copy of source
	 
	 
	 */

	void init();
	/*
	 * PRE- 
	 * POST- The stack is empty
	 */
	
	void push();
	/*
	 * PRE- 
	 * POST- A copy of element is now on top of the stack
	 */

	void pop();
	/*
	 * PRE- The stack is not empty
	 * POST- The top of the stack-PRE is returned and deleted.
	 */
	
	void top();
	/*
	 * PRE- The stack is not empty
	 * POST-A copy of the top of the stack has been returned.
	 */
	
	boolean isEmpty();
	/*
	 * PRE- 
	 * POST- true:  The amount of elements of the stack equals 0
	 * false: the amount of elements of the stack is greater than 0.
	 */
	
	void difference();
	/*
	 * PRE- 
	 * POST- Returns the differences
	 */

	int size();
	/*
	 * PRE- 
	 * POST- The amount of elements of the stack has been returned
	 */
	void intersection();
	/*
	 * PRE- 
	 * POST- Returns the similarities
	 */

	void Union();
	/*
	 * PRE- 
	 * POST- Returns both
	 */

	void symDifference();
	/*
	 * PRE- 
	 * POST- Returns the SymDifference
	 */

	void end();
	/*
	 * PRE-CTRL D is pressed 
	 * POST- The program ends
	 */

	boolean nextCharIs();
	/*
	 * PRE- 
	 * POST- returns where a specific character can be read by nextChar();
	 */
	
	
}
