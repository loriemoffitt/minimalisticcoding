<h1>Tansaction Report</h1>

```
type Tx = {
    date: Date
    product: string
    affiliate: string
    coupon: string
    txn: string
    status: 'open' | 'settled'
    amount: string
}
```

<h2>Transaction Totals</h2>

```
type TxTotals = {
   totalSales: string,
   grossIncome: string, 
   totalRefunds: string, 
   grossRefunds: string,
   refundRate: string,
   netSales: string, 
   netIncome: string
}
```

<h1>Paid to Affiliate Report</h1>

```
type PdAffiliate = {
    affiliate: string,
    sales: string,
    amtPaid: string,
}
```

<h2>Paid to Affiliates Totals</h2>

```
type PdAffiliateTotals = {
  totalSales: string,
  amountPaid: string, 
}
```

<h1>Sales Report</h1>

```
type Sales = {
    affiliate: string,
    product: string,
    visitors: number, 
    sales: number, 
    conversions: string, 
    perVisitor: string, 
    perSale: string, 
    total: string
}
```

<h2>Sales Totals</h2>

```
type SalesTotals = {
  visitors: string, 
  sales: string, 
  conversions: string, 
  perVisitor: string, 
  perSale: string, 
  total: string
}
```

<h1>PreApprovals Report</h1>

```
type PreApprovals = {
    product: string,
    affiliate: string,
    email: string, 
    currMax: string,
    current: string, 
    status: string, 
    nextDate: Date, 
}
```

<h1>PreApproval Failures Report</h1>h

```
type PreApprovalFailure = {
    typeReason: string, 
    numberOfFailures: number,
}
```

<h1>PreApprovals Forecast Report</h1>

```
type PreApprovalForecast = {
    product: string
    subscriptions: number
    total: string
}
```

<h2>PreApprovals Forecast Totals </h2>

```
type PreApprovalForecastTotals = {
  thirtyDay: string
  sixtyDay: string
  oneEightyDay: string
  threeSixtyFiveDay: string
}
```

<h1>VAT Transaction Report</h1>

```
type VatTransaction = {
    vendorCountry: string, 
    date: Date, 
    txn: string, 
    name: string, 
    ip_address: string, 
    subTotal: string, 
    taxCollected: string
}
```
