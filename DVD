/**
 * @author Sara Liu
 * 10/16/20
 * This class represents a DVD object. 
 * The tax rate on DVDs is 3%
 */
public class DVD extends AmazonProduct {
	final double taxRate = 0.03;
	/**
	 * A DVD is automatically assigned to 
	 * the entertainment category
	 * @param price
	 * @param name
	 * @param primeShipping
	 */
	public DVD(double price, String name, boolean primeShipping) {
		super(price, name, CategoryOptions.ENTERTAINMENT, primeShipping);
	}
	/**
	 * Calculate the tax on DVDs. The tax rate for DVDs is 3%
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
