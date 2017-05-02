# -*- coding:utf-8 -*-
class Solution:
    #快排
    def Quicksort(self,tinput,start,end):
        if start<end:
            divIndex = self.partition(tinput,start,end)
            self.Quicksort(tinput,start,divIndex)
            self.Quicksort(tinput,divIndex+1,end)
        else:
            return
        
    def partition(self,tinput,start,end):
        i = start -1
        for j in range(start,end):
            if tinput[j]<= tinput[end]:
                i+=1
                temp = tinput[i]
                tinput[i] = tinput[j]
                tinput[j] = temp
        temp2 = tinput[end]
        tinput[end] = tinput[i+1]
        tinput[i+1] = temp2
        return i
