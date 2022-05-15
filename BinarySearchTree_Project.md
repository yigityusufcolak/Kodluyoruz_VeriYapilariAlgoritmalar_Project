# Binary Search Tree Project
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Binary Search Tree 
1- The left subtree of a node contains only nodes with keys lesser than the node’s key.

2- The right subtree of a node contains only nodes with keys greater than the node’s key.

3- For given array ;

 - Root is 7 
 
  5<7 ,so left of 7
  
                                                  7
                                            5




             
  1<7 & 1<5 ,so   left of 5 
                                               
                                               7
                                        5
                          
                                   1  
 8>7 ,so  right of 7
                                              
                                               7
                                        5             8
                          
                                   1  

 
 
 3<7 & 3<5 & 3>1 ,so  right of 1
                                             
                                               7
                                        5             8
                          
                                   1                                             
                                        3





6<7 & 6>5 ,so  right of 5

                                              
                                               7
                                        5             8
                          
                                   1        6                                     
                                        3




 
   0<7 & 0<5 & 0<1 ,so  left of 1


                                              
                                               7
                                        5             8
                          
                                   1        6                                     
                              0          3






9>7 & 9>8 ,so right of 8

                                              
                                               7
                                        5             8
                                                            9
                                   1        6                                     
                              0          3

4<7 & 4<5 & 4>1 & 4>3  right of 3


                                              
                                               7
                                        5             8
                                                            9
                                   1        6                                     
                              0          3
                                              4

2<7 & 2<5 & 2>1 & 2<3 left of 3

                                              
                                               7
                                        5             8
                                                            9
                                   1        6                                     
                              0          3
                                      2       4


