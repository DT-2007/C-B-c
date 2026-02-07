#%%
import random
print("---sản phẩm lập trình của Chu Quang Lộc---")
Q=10000000
q="vnd"
e="tai"
f="xiu"
print("So du tai khoan =",Q,q)
S=input("-nhap 'tai xiu' hoac 'lo de' de bat dau tro choi:")
if S=="tai xiu":
	while True:
	    s=int(input("-xin moi ban dat cuoc:"))
	    if s>Q:
	    	print("-so tien ko du de cuoc")
	    	break
	    w=input("-tai or xiu:")
	    val1=random.randint(1,6)
	    print(val1)
	    t=input()
	    val2=random.randint(1,6)
	    print(val2)
	    y=input()
	    val3=random.randint(1,6)
	    print(val3)
	    if val1+val2+val3<=10:
		    print("-xiu")
		    if w==f:
			    Q=Q+s
			    print("-chuc mung ban")
		    else:
			    Q=Q-s
			    print("-thanh that chia buon")
	    if val1+val2+val3>10:
		    print("-tai")
		    if w==e:
			    Q=Q+s
			    print("-chuc mung ban")
		    else:
		    	Q=Q-s
		    	print("-thanh that chia buon")
	    print("-so du tai khoan =",Q,q)
	    if Q<=0:
	    	Q=20000
	    	print("-nhà cái thấy bạn quá tội nghiệp nên đã từ thiện bạn 20000vnd")
	    	print("-So du tai khoan",Q,q)
	    r=input("-ban muon tiep tuc khong:")
	    if r=="khong" or r=="ko":
	    	break
if S=="lo de":
	while True:
	    de=int(input("-xin moi dat cuoc:"))
	    if de>Q:
	    	print("-so tien ko du de cuoc")
	    	break
	    DE=int(input("-moi chon so de:"))
	    ld=random.randint(0,99)
	    print("giai dac biet:",ld)
	    a=input()
	    id=random.randint(0,99)
	    print("giai nhat:",id)
	    b=input()
	    iD=random.randint(0,99)
	    pd=random.randint(0,99)
	    print("giai nhi:",iD,pd)
	    input()
	    pD=random.randint(0,99)
	    Pd=random.randint(0,99)
	    PD=random.randint(0,99)
	    od=random.randint(0,99)
	    Od=random.randint(0,99)
	    oD=random.randint(0,99)
	    print("giai ba:",pD,Pd,PD,od,Od,oD)
	    c=input()
	    ad=random.randint(0,99)
	    Ad=random.randint(0,99)
	    aD=random.randint(0,99)
	    AD=random.randint(0,99)
	    print("giai tu:",ad,Ad,aD,AD)
	    d=input()
	    sd=random.randint(0,99)
	    sD=random.randint(0,99)
	    Sd=random.randint(0,99)
	    SD=random.randint(0,99)
	    ed=random.randint(0,99)
	    Ed=random.randint(0,99)
	    print("giai nam:",sd,sD,Sd,SD,ed,Ed)
	    e=input()
	    wd=random.randint(0,99)
	    Wd=random.randint(0,99)
	    wD=random.randint(0,99)
	    print("giai sau:",wd,Wd,wD)
	    f=input()
	    rd=random.randint(0,99)
	    Rd=random.randint(0,99)
	    rD=random.randint(0,99)
	    RD=random.randint(0,99)
	    print("giai khuyen khich:",rd,Rd,rD,RD)
	    input()
	    if DE==ld:
	    	Q=Q+de*10000
	    	print("bạn trúng giải đặc biệt")
	    if DE==id:
	    	Q=Q+de*2000
	    	print("bạn trúng giải nhất")
	    if iD==DE or pd==DE:
	    	Q=Q+de*500
	    	print("bạn trúng giải nhì")
	    if pD==DE or pd==DE or PD==DE or od==DE or Od==DE or oD==DE:
	    	Q=Q+de*100
	    	print("bạn trúng giải ba")
	    if ad==DE or Ad==DE or aD==DE or AD==DE:
	    	Q=Q+de*50
	    	print("bạn trúng giải tư")
	    if sd==DE or sD==DE or Sd==DE or SD==de or ed==DE or Ed==DE:
	    	Q=Q+de*20
	    	print("bạn trúng giải năm")
	    if wd==DE or wD==DE or Wd==DE:
	    	Q=Q+de*10
	    	print("bạn trúng giải sáu")
	    if rd==DE or Rd==DE or rD==DE or RD==DE:
	    	Q=Q+de*2
	    	print("bạn trúng giải khuyến khích")
	    if id!=DE and ld!=DE and iD!=DE and pd!=DE and Pd!=DE and pD!=DE and PD!=DE and od!=DE and Od!=DE and oD!=DE and ad!=DE and Ad!=DE and aD!=DE and AD!=DE and sd!=DE and sD!=DE and Sd!=DE and ed!=DE and Ed!=DE and wd!=DE and Wd!=DE and wD!=DE and rd!=DE and rD!=DE and Rd!=DE and RD!=DE:
	    	Q=Q-de
	    	print("bạn không trúng giải")
	    print("-So du tai khoan =",Q,q)
	    if Q<0:
	    	print("-hết tiền rồi,bán xe bán nhà đi rồi quay lại đây=))")
	    	break
	    dea=input("-ban co muon tiep tuc ko:")
	    if dea=="ko" or dea=="khong":
	    	break
