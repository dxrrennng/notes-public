```mermaid
flowchart TD;
	Injections --> Firms
	Firms-.g&s..-> Households
	Households --payment for g&s--> Firms
	Firms --factor payments--> Households
	Households -.FoP..->Firms
	Households --> Leakages
	linkStyle 2,3 stroke:blue,stroke-width:4px;
	linkStyle 1,4 stroke:red,stroke-width:10px;
```

