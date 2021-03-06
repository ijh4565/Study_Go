 **GoLang 공부**
================
# 교재 : Tucker의 Go 언어 프로그래밍
-------------
## From : 2022.05.31
<br/>   

### Init &nbsp; : &nbsp; 상위 폴더에서   
    go mod init Directory_Name
<br/>

### Build &nbsp; : &nbsp; 해당 디렉토리 내에서 
    go build
<br/>

### 외부 패키지 이용 &nbsp; : &nbsp; import에 "package_link" 후 go.mod 폴더에서 
    go mod tidy
<br/>

### Local Package 이용 &nbsp; : &nbsp; import &nbsp; ```"mod_name/mod_directory/directories.../package name"```
<br/>

### Test &nbsp; : &nbsp; Test Code는 ```(main)_test.go``` 형식으로 작성 후 해당 디렉토리에서 
    go test

### 개별 Test 수행 
    go test -run (Test 함수 이름) 
<br/>

### Benchmark &nbsp; : &nbsp; Test를 여러 번 반복 수행
Test Code 내에 ```func BenchmarkXxxxx(b *testing.B)``` 형식으로 작성 후
    go test -bench
<br/>

### Package 다운로드 &nbsp; 
    go get (package_link)   
<br/>



<br/>   

## 날짜 별     
<br/>   

> 22.05.31
>> Today's Song : Silk Sonic - 777  
>>
>> <img src = "https://image.yes24.com/goods/105016742/XL" width= "100px">    
>>
>>> **hello** : Hello Go World   
>>> **Var** : Var Type, Declare, Change Type   
>>> **FMT** : Standard I/O

<br/>

> 22.06.01
>> Today's Song : Anne Mari, Niall Horan - Our Song    
>>
>> <img src = "https://blog.kakaocdn.net/dn/4saAU/btq5vESBKHp/PyL2I5NK91kdDUVsxfZkV1/img.jpg" width= "110px">
>> 
>>> **Calc** : Basic Calculation   
>>> **Func** : Declare Function, Recursive   
>>> **Const** : Declare Constant, Using iota

<br/>

> 22.06.03
>> Today's Song : NVTHVN, Forrest - Dancing in the living room    
>>
>> <img src = "https://m.media-amazon.com/images/I/81MYQtKxwjL._SS500_.jpg" width= "110px">
>> 
>>> **If** : Basic If, Multi If, Initial;Condition   
>>> **Switch** : Basic Switch, Condition, Const iota, Fallthrough   
>>> **For** : Basic For, Continue / Break, Multi For & Lable    
>>> **Array** : Decleare Array, Range, Multidimensional Array

<br/>

> 22.06.07
>> Today's Song : Arizona Zervas - Roxanne    
>>
>> <img src = "https://image.bugsm.co.kr/album/images/500/9549/954900.jpg" width= "110px">
>> 
>>> **Structure** : Declare & Initialize Structure    
>>> **Pointer** : Declare  Initialize Pointer, Instance, Garbage Collector   
>>> **String** : "" vs ``, rune, range, Immutable    
>>> 

<br/>

> 22.06.08
>> Today's Song : Powfu - Death Bed(coffee for yout head)    
>>
>> <img src = "https://www.wrmf.com/wp-content/uploads/2020/06/M_PowfuDeathbed_053120.jpg" width= "110px">
>> 
>>> **Package** : Declare Package, Module, go.mod, go.sum    

<br/>

> 22.06.09
>> Today's Song : BRELAND - My Truck    
>>
>> <img src = "https://cdns-images.dzcdn.net/images/cover/ffe79d067c31a4709077e73a163acae3/500x500.jpg" width= "110px">
>> 
>>> **HitNum** : Stdio, Random Int, Seed, Time    
>>> **SlotEX** : Stdio, Random Int, Seed, Time    
>>> **Slice** : Declare, Append, Delete, Copy ...    

<br/>

> 22.06.10
>> Today's Song : Tracy Chapman - Give Me One Reason    
>>
>> <img src = "https://i.scdn.co/image/ab67616d0000b2736b38571f15487588ed53032f" width= "110px">
>> 
>>> **Method** : Declare Method, Pointer, Value    
>>> **Interface** : Using Interface with Module, Convert to Another Interface or Concrete Type    
>>> 

<br/>

> 22.06.13
>> Today's Song : Monsune - Outta My Mind    
>>
>> <img src = "https://image.bugsm.co.kr/album/images/500/203565/20356570.jpg" width= "110px">
>> 
>>> **Function2** : Args, defer, Literal    
>>> **DataStructure** : Queue, Stack

<br/>

> 22.06.14
>> Today's Song : Forrest, Biskwiq - Why Not Me    
>>
>> <img src = "https://c.saavncdn.com/435/Warm-English-2018-20190113200524-500x500.jpg" width= "110px">
>> 
>>> **DataStructure2** : Ring, Map    
>>> **Error** : Error Handling, Recover

<br/>

> 22.06.16
>> Today's Song : Earth, Wind & Fire - September    
>>
>> <img src = "https://i.discogs.com/5yxzXA5_vxownzJtVUYJq7QJEsVhlYSnyMdNtT6Y1DA/rs:fit/g:sm/q:40/h:300/w:300/czM6Ly9kaXNjb2dz/LWRhdGFiYXNlLWlt/YWdlcy9SLTI5OTMw/OC0xNDc1NDExMzUy/LTk1ODUuanBlZw.jpeg" width= "110px">
>> 
>>> **Go Routine** : Lock, WaitGroup, Mutex    
>>> **Channel** : Channel, Context

<br/>

> 22.06.17
>> Today's Song : Daft Phunk - Harder, Better, Faster, Stronger    
>>
>> <img src = "https://image.genie.co.kr/Y/IMAGE/IMG_ALBUM/079/966/905/79966905_1503049100047_1_600x600.JPG/dims/resize/Q_80,0" width= "110px">
>> 
>>> **SearchWord** : filepath.Glob, Scan    
>>> **SearchWord2** : channel    

<br/>

> 22.06.21
>> Today's Song : TroyBoi - ili     
>>
>> <img src = "https://is2-ssl.mzstatic.com/image/thumb/Music115/v4/00/89/70/008970b7-2435-d7c9-4a40-ed633c9f8086/4430.jpg/400x400bb.jpg" width= "110px">
>> 
>>> **SOILID** : SRP, OCP, LSP, ISP, DIP    
>>> **Test** : Testing Code, Benchmark    

<br/>

> 22.06.22
>> Today's Song : Jay Park - Yacht     
>>
>> <img src = "https://image.bugsm.co.kr/album/images/500/201085/20108568.jpg" width= "110px">
>> 
>>> **Web Server** : Request, File Server, Test, ServeMux    
