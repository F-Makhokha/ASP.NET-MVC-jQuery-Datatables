# ASP.NET-MVC-jQuery-Datatables
Price Quotation Table with jQuery Datatables (ASP.NET MVC)

In order to make datatable work, we should place our scripts in the following order.

```C#
<link href="https://cdn.datatables.net/v/dt/dt-1.10.18/datatables.min.css" rel="stylesheet" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/1.10.19/js/jquery.dataTables.min.js"></script>
<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/buttons/1.5.4/js/dataTables.buttons.min.js" ></script>
<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/buttons/1.5.4/js/buttons.flash.min.js"></script>
<script type="text/javascript" language="javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.1.3/jszip.min.js"></script>
<script type="text/javascript" language="javascript" src="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.36/pdfmake.min.js"></script>
<script type="text/javascript" language="javascript" src="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.36/vfs_fonts.js"></script>
<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/buttons/1.5.4/js/buttons.html5.min.js"></script>
<script type="text/javascript" language="javascript" src="https://cdn.datatables.net/buttons/1.5.4/js/buttons.print.min.js"></script>
```

T-SQL Database Code:

```SQL
CREATE TABLE [dbo].[Table] (
    [QuoteID]      NCHAR (10) NOT NULL,
    [CustomerName] NCHAR (40) NOT NULL,
    [Description]  NCHAR (40) NOT NULL,
    [Quantity]     FLOAT (53) NOT NULL,
    [UnitPrice]    FLOAT (53) NOT NULL,
    [VatRate]      FLOAT (53) NOT NULL,
    [SubTotal]     FLOAT (53) NOT NULL,
    [TotalAmount]  FLOAT (53) NOT NULL,
    PRIMARY KEY CLUSTERED ([QuoteID] ASC)
);
```

![alt text](https://i.ibb.co/s68fn03/a1.png)


![alt text](https://i.ibb.co/C63D2z7/a2.png)


![alt text](https://i.ibb.co/ysXCYT3/Przechwytywanie.png)


![alt text](https://i.ibb.co/4dnyWHQ/Przechwytywanie.png)


