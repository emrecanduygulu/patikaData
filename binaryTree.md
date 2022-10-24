## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

*   Root 7'dir.

*   5, 7'den küçük olduğu için root'un sol tarafında yazılır.

 *   1, 7'den ve 5'ten küçük olduğu için 5'in sol tarafına yazılır.

  *  8, 7'den büyük olduğu için 7'nin sağ tarafına yazılır.

   * 3, 7'den ve 5'ten küçük; 1'den büyük olduğu için 1'in sağ tarafına yazılır.

  * 6, 7'den küçük 5'den büyük olduğu için 5'in sağ tarafına yazılır.

  *  0, hepsinden küçük olduğu için kendinden önceki en küçük sayı olan 1'in sol tarafına yazılır.

  *  9, hepsinden büyük olduğu için kendinden önceki en büyük sayı olan 8'in sağ tarafına yazılır.

  *  4, 7 ve 5'ten küçük; 1 ve 3'ten büyük olduğu için 3'ün sağ tarafına yazılır.

  *  2, 7 ve 5'ten küçük; 1'den büyük ve 3'ten küçük olduğu için 3'ün sol tarafına yazılır.
