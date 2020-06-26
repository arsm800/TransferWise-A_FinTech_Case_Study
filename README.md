# TransferWise – A FinTech Case Study


## Overview and Origin

TransferWise is an online money transfer services that makes it easy for people send and receive money in a variety of currencies.  It was founded in 2011 by Kristo Kaarmann and Taavet Hinrikus.  While working in London, Kaarmann and Hinrikus regularly sent money back to their native country of Estonia.  This proved to be extremely costly; the bank charges on their international money transfers where they needed to convert from Pounds to Euros were sometimes 5% of the total value of the transfer.  

Paying such a huge amount of their earnings in fees inspired Kaarmann and Hinrikus to found TransferWise.  TransferWise is backed by many venture capital firms, including Vitruvian Partners, BlackRock, JP Morgan, and Andreessen Horowitz.  As of May 2019, TransferWise had raised $772 million at a valuation of $3.5 billion.  After six years, TransferWise announced that It was finally profitable in 2017.  In 2018, TransferWise recorded revenues of $148.61 million while earning a profit of $7.88 million.


## Business Activities

TransferWise provides a platform for users to make international payments for an affordable cost.  It eliminates foreign currency fees by not actually have to undergo any foreign currency conversions.  TransferWise has a network of bank accounts in every country that can make and receive payments.  When an individual or organization makes a payment, they transfer money to TransferWise’s bank account in that individual’s country.  Simultaneously, a bank transfer from TransferWise’s account in the receiving individual’s country is made to the receiving individual.  TransferWise crowd-sources transactions going in the opposite direction to keep all its bank accounts funded.  This structure allows TransferWise to avoid paying hefty foreign currency transaction fees and enables them to charge a lower rate.

Since 2017, TransferWise has been utilizing AWS infrastructure for all of their workloads.  All the code resides on GitHub.  Their backend is primarily written in Java, but there are parts written in Kotlin, Go, Python, and NodeJS.  Their frond end is built in React.  TransferWise also offers API capabilities, too, which allow its service to integrate with many banking and commercial platforms.


## Landscape

TransferWise falls into the cross-border payments domain within the broader FinTech industry.  This specific domain can be thought of as encompassing blockchain and non-blockchain payment types through traditional and non-traditional processes and technologies.

Two of the most traditional international  payment facilitators that still dominate the space are SWIFT and Western Union.  SWIFT is a secure environment created in 1973 that allows more than 10,000 financial institutions to send secure payment orders.  Western Union was founded in 1850 as a telegraph service provider.  Over 100 years later the company began specializing in cross-border P2P payments.  

These aforementioned companies stand the most to lose as more innovative companies enter this domain with newer and non-traditional technology.  Paypal has become an established leader of online payments and money transfers between both individuals and businesses.  Stripe (founded in 2010), one of Paypal’s primary competitors, offers similar services, but is more customizable than Paypal.  TransferWise utilizes the Hawala money transfer system, which allows them to reduce the costly fees.  There are number of companies that are banking on cryptocurrencies (a new technology) to become the standard bearer for international money transfers.  Regardless of which companies emerge victorious, these technologies are revolutionizing the international remittance industry—making it easier and more affordable for more people to send money abroad.  


## Results

According to their 2019 annual report, TransferWise processes over 4 billion pounds in transactions every month.  The average price of a transfer is .67%, down from .73% in 2017.  20% of all transfers are made in under 20 seconds.  According to The World Bank, the global average total cost of remittance is 6.94%.  54% of their revenue came from their European market,  25% from the United States, and 21% from the rest of the world.


## Recommendations

There are a number of ways TransferWise can approach the future.  Right now, TransferWise’s target customers are individuals and small to medium-sized businesses.  Since their revenues are heavily to the size of the transaction, they may want to start targeting large businesses.  If they are charging roughly 4% less than other traditional banks and clearinghouses, the savings will only increase with larger transactions.

TransferWise may also want to diversify their existing small and medium-sized business customers.  When I worked for an accounting firm, we had a number of non-profit clients that transferred large amounts of money to foreign countries.  For many of our smaller clients, cloud-based accounting software fits their needs.  Many of these cloud-based accounting software programs connect with 3rd party vendors offering a variety of financial services.  Since TransferWise’s allows their platform to be integrated with a variety of commercial platforms, partnering with programs like Quickbooks Online might open up a whole new customer demographic.

Lastly, TransferWise can increase their presence in payments between individuals and vendors.  Their borderless Mastercard debit card launched in the USA in 2019.  This debit card connects to TransferWise customers’ borderless accounts, where they can use the currency funds in their account to pay for purchases in other countries that require different currencies.  This allows customers to bypass foreign transactions fees, because either they will be paying from that particular currency already in their account or it will be converted with TransferWise’s low fee rate.

From a risk standpoint, there may be some regulatory and compliance issues that may affect the specific services TransferWise offers and how it should be accounted for.  In addition, as the industry becomes more competitive with more companies focusing on lowering the fees of international payments, TransferWise’s cost savings will not always be its unique selling proposition.  As a result, tt would be wise to diversify its line of services  and revenue streams; new products like the Mastercard debit card indicate that this is the direction TransferWise is going.


## Citations

TransferWise: [2019 Annual Report](https://transferwise.com/gb/blog/annualreport2019)

TransferWise: [Website](https://transferwise.com/us)

Product Mint: [The TransferWise Business Model - How Does TransferWise Work & Make Money](https://productmint.com/the-transferwise-business-model-how-does-transferwise-make-money/#TransferWise_Valuation,_Funding,_Revenue_Potential_IPO)

Stackshare: [TransferWise Profile](https://stackshare.io/transferwise#stacks)

The FinTech Times: [Modern Techbology for Cross-Border Payments](https://thefintechtimes.com/cross-border-payments/)

Medium: [The TransferWise Stack, 2020 Edition](https://medium.com/transferwise-engineering/the-transferwise-stack-2020-edition-68f70267501b)
