def multiplication_table() -> str :
    '''
    return a string of multiplication table within one line
    '''
    return '\n'.join(['\t'.join(['%s*%s=%-2s'%(y, x, x*y) for y in range(1, x+1)]) for x in range(1, 10)])
    
    # ----Another Way
    # s = ''                               
    # for i in range(1, 10) :             
    #     for j in range(1, i+1) :        
    #         s += '%d*%d=%d'%(j, i, i*j) 
    #         s += '\t' if j != i else '' 
    #     s += '\n' if i != 9 else ''     
    # return s                            
    # ----
