l=[]
ch=0
while(ch<4):
    print(" DAY IN DAY OUT STORES")
    print(" 1 for adding info ")
    print(" 2 to remove info")
    print(" 3 detail trans")
    print("4 for exit" )
    print("enter choice")
    ch = int(input())
    if ( ch==1):
        ans=input("input choice y or n")
        while (ans =='y' or ans == 'Y'):
            dic ={}
            dic["name"] = input("name")
            dic['item'] = (input("item"))
            dic["qty"] = int(input("qty"))
            dic["rate"] = int(input("rate"))
            dic["trans"] = dic["qty"] * dic["rate"]
            dic["cno"] = int(input("cno"))
            l.append(dic)
            ans=input("do you y/n")
    elif(ch==2):
        if(l == []):
           print("list empty")
        else:

            c=0
            fl=0
            rem=input("enter name info to remove")
            for v in l:
                  if rem==v["name"]:
                     l.pop(c)
                     fl=1
                     break
            c=c+1
            if(fl==0):
               print("not found")

    elif(ch==3):
        if (l == []):
           print("list empty")
        else:
           no=int(input("enter number u want to check"))
           print(" DAY IN DAY OUT")
           for v in l:
              if v["cno"] == no:
                 print("name", "                                       ", v["name"])
                 print("item", "                                       ", v["item"])
                 print("qty", "                                        ", v["qty"])
                 print("rate", "                                       ", v["rate"])
                 print("trans", "                                      ", v["trans"])
                 print("cno", "                                        ", v["cno"])



