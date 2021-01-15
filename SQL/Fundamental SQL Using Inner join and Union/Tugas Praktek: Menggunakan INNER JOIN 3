SELECT
    tr_penjualan.kode_transaksi,
    tr_penjualan.kode_pelanggan,
    tr_penjualan.kode_produk,
    ms_produk.nama_produk,
    ms_produk.harga,
    tr_penjualan.qty,
    ms_produk.harga * tr_penjualan.qty AS total
FROM
    tr_penjualan
    INNER JOIN ms_produk ON tr_penjualan.kode_produk = ms_produk.kode_produk;
