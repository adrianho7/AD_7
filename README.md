# 姓名 何銘恆
## 學號 0624102
### 高雄科技大學(第一校區)
#### 資訊管理學係
##### 三年級B班

:shirt:

:shoe:

:watch:

`何謂潮流?`

```
潮流 不是 跟風 
而是 穿出 自己的 風格
```

*潮流* ~~不是跟風~~ 
而是穿出
**自己的風格**

>Bape
>>Aape

Facourite Brand:
+ xVESSEL
+ McQueen
+ SMUDGE

[Xiao Pi Hai小屁孩] <https://www.youtube.com/channel/UCS689tLcNTRejDH2uCULLdA>

|Supreme|Palace|A Bathing Ape|
|:----------|:----------:|----------:|
|Box Logo|Triangle|Deaf|
|US|UK|JPN|

```
package com.amazonaws.polly.samples;
 
import com.amazonaws.services.polly.AmazonPolly;
import com.amazonaws.services.polly.AmazonPollyClientBuilder;
import com.amazonaws.services.polly.model.DeleteLexiconRequest;
 
public class DeleteLexiconSample {
    private String LEXICON_NAME = "SampleLexicon";
 
    AmazonPolly client = AmazonPollyClientBuilder.defaultClient();
 
    public void deleteLexicon() {
        DeleteLexiconRequest deleteLexiconRequest = new DeleteLexiconRequest().withName(LEXICON_NAME);
 
        try {
            client.deleteLexicon(deleteLexiconRequest);
        } catch (Exception e) {
            System.err.println("Exception caught: " + e);
        }
    }
}
```


