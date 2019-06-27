'# 見出し1'
# 見出し1

'## 見出し2'
## 見出し2

'### 見出し3'
### 見出し3

'#### 見出し4'
#### 見出し4

'##### 見出し5'
##### 見出し5

'###### 見出し6'
###### 見出し6

'- リスト1
    - ネスト リスト1_1
        - ネスト リスト1_1_1
        - ネスト リスト1_1_2
    - ネスト リスト1_2
- リスト2
- リスト3'
- リスト1
    - ネスト リスト1_1
        - ネスト リスト1_1_1
        - ネスト リスト1_1_2
    - ネスト リスト1_2
- リスト2
- リスト3

1. 番号付きリスト1
    1. 番号付きリスト1_1
    1. 番号付きリスト1_2
1. 番号付きリスト2
1. 番号付きリスト3

> 引用
> 
> 引用　引用

> 引用
> 
>> 引用　引用
>> 
>> 引用　引用　引用

    # Tab
    class Hoge
        def hoge
            print 'hoge'
        end
    end

---

    # Space
    class Hoge
      def hoge
        print 'hoge'
      end
    end
    
インストールコマンドは `gem install hoge` です
    
normal *italic* normal
normal _italic_ normal

normal **bold** normal
normal __bold__ normal

normal ***italicbold*** normal
normal ___italicbold___ normal

***

___

---

*    *    *

###[表示文字](リンクURL)
[Google](https://www.google.co.jp/)


~~取り消し線~~



　~~~ruby
　class Hoge
　  def hoge
　    print 'hoge'
　  end
　end
　~~~
 
 
|header1|header2|header3|
|:--|--:|:--:|
|align left|align right|align center|
|a|b|c|
