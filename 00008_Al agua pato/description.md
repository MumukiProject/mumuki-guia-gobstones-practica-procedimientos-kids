Por una cuestión estratégica, Willie colocó los estanques en las esquinas Noroestes ↖ (borde al Norte y al Oeste) de sus plantaciones. Tendremos que movernos hasta él para recolectar agua; pero como cada plantación tiene un tamaño distinto, no podremos usar la primitiva `Mover Norte` o `Mover Oeste` (porque no sabremos cuántas parcelas movernos). 

En su lugar, tendremos otra primitiva `IrAlBorde` a la que le podremos indicar la dirección en la que queremos movernos todo lo que podamos hasta llegar al borde. ¡Veamos cómo funciona! 

> Definí el procedimiento `Recolectar Del Estanque` que mueva el tractor hasta el estanque y recolecte agua (sacando dos bolitas azules).