# Excel Critical Point Calculator

Interactive HTML version of an Excel worksheet for critical point / break-even calculation.

## Portfolio purpose

This project shows how a spreadsheet-based calculation can be converted into a small browser-based calculator. The original Excel task calculated production amount, revenue, fixed costs, variable costs, total costs, profit, and profit percentage.

## Live HTML

The main calculator is in [`index.html`](index.html).

## Original evidence

The original exported task/report is included as PDF evidence:

- [`Tehtävä 1 Kriittinen piste(1).pdf`](Teht%C3%A4v%C3%A4%201%20Kriittinen%20piste(1).pdf)

## Original values

| Input | Value |
|---|---:|
| Start amount | 8 units/month |
| Step | 1 unit |
| Machine selling price | 890 €/unit |
| Fixed costs | 1900 €/month |
| Manufacturing and material costs | 700 €/unit |

## Formulas

```text
Net sales = production amount × selling price
Variable costs = production amount × variable cost per unit
Total costs = fixed costs + variable costs
Profit = net sales − total costs
Profit percentage = profit / net sales
Critical point = fixed costs / (selling price − variable cost per unit)
```

## Files

| File | Description |
|---|---|
| `index.html` | Interactive calculator converted from the Excel model |
| `Tehtävä 1 Kriittinen piste(1).pdf` | Original PDF evidence exported from the spreadsheet task |

## Skills demonstrated

- Excel calculation logic
- Break-even analysis
- HTML/CSS/JavaScript conversion
- Interactive input handling
- Responsive user interface design
- Technical documentation

## License

MIT License
