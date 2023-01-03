# Day-1
list=['microsoft','google','ibm','dell','tcs','hcl','oracle','tech mahindra','l&t','wipro','infosys','cognizant','mindtree','honeywell','microland','ramco','sonata','zensar','vmare','twillio','sage','citrix','acciva','datastax','nebula','pts','citrix','splunk','adp','intuit']
print(list)
print(len(list)) #len() is used to find the length of string
list[5]='salesforce'#to assign values at certain index
print(list)
list.append('hp') #append() is used to add values to list at end
print(list)
list.insert(6,'asus') #insert(index,element) is used to add values anywhere in the list using index
print(list)
list.remove('sage') #remove() is used to remove an element which we don't know the index value
print(list)
del list[3] #del is used to delete an element at particular index
print(list)
list.pop() #pop() is used to remove last element
print(list)
list.pop(6) #pop(index) is used to remove certain element by using index
print(list)
list.sort() #sort() is used to sort the elements in the list
print(list)
list.sort(reverse=True) #sort(reverse=True) is used to reverse the elements in alphabetical order
print(list)
list.reverse() #reverse() is used to reverse the elements in array
print(list)
