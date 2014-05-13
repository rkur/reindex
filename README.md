reindex
=======

\\tablelist

  \\ list A
  @dbo.CustInvoiceJour 
  @dbo.SalesTable
  @dbo.CustTrans
  @dbo.CustTransOpen
  @dbo.InventSum
  
  \\ list B	
  @dbo.VendPackingSlipJour
  @dbo.VendPackingSlipTrans
  @dbo.VendInvoiceJour
  @dbo.VendInvoiceTrans


\\preparation

  create table www_reindex_stat
  create table www_reindex_stat_index_all_log
  
  create www_reindex_stat_log
  create www_reindex_stat_index_all_log
  
  create www_reindex_InventSum
  create www_reindex_SalesTable
  create www_reindex_CustInvoiceJour
  create www_reindex_*
  create www_reindex_*
  create www_reindex_*
  create www_reindex_*

\\ run

  exec www_reindex_InventSum 
  exec www_reindex_SalesTable
  exec www_reindex_CustInvoiceJour
  exec www_reindex_
  exec www_reindex_
  exec www_reindex_
  exec www_reindex_
  exec www_reindex_
  exec www_reindex_
  
\\ log

  use ax_molniya
  GO
  select * from www_reindex_stat
  select * from www_reindex_stat_index_all
  
