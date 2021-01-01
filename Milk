/**
 * @author Sara Liu
 * 10/16/20
 * This class represents a Milk object. 
 * The tax rate on milk is 1%
 */
public class Milk extends AmazonProduct{
	final double taxRate = 0.01;
	/**
	 * Milk is automatically assigned to 
	 * the Produce category
	 * @param price
	 * @param name
	 * @param primeShipping
	 */
	public Milk(double price, String name, boolean primeShipping) {
		super(price, name, CategoryOptions.PRODUCE, primeShipping);
	}
	/**
	 * Calculate the tax on Milk. The tax rate for Milk is 1%
	 */
	@Override
	public double calcTax() {
		return this.getPrice()*taxRate;
	}

	@Override
	public boolean isCouponEligible() {
		return true;
	}

}
