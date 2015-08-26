

[TOC]



``` objective-c
NSlog(@"hello world")
```

# 标题一

## 标题二

### 标题三

#### 标题四

##### 标题五

标题六

**哈哈**

*算了吧*

### 超链接测试

[myblog](www.baidu.com)

### 引用测试

> 很多人所谓的正义感其实是很廉价的



> 举头望明月 
> 
> 低头思故乡

## 代码块测试

``` objective-c
- (void)viewDidLoad
{
    [super viewDidLoad];
	// Do any additional setup after loading the view, typically from a nib.
}

- (void)touchesBegan:(NSSet *)touches withEvent:(UIEvent *)event
{
    // 1.URL
    NSURL *url = [NSURL URLWithString:@"http://www.baidu.com"];

    // 2.请求
    NSURLRequest *request = [NSURLRequest requestWithURL:url];

    // 3.发送请求
    [NSURLConnection sendAsynchronousRequest:request queue:[NSOperationQueue mainQueue] completionHandler:^(NSURLResponse *response, NSData *data, NSError *connectionError) {
        NSString *str = [[NSString alloc] initWithData:data encoding:NSUTF8StringEncoding];
        NSLog(@"%@", str);
    }];
}
```

``` c
int i = 10;
double d = 2.5;
```

水电费

第三方

- 哈哈
  
  - 第三方
    
    但是飞
    
    水电
    
    ​
  
  ​