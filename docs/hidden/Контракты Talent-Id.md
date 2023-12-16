---
share: "true"
---

[[../Тех. документация/Тех.  документация Talent-Id|Тех.  документация Talent-Id]]

Дима, Работа, [1 дек. 2023 г., 11:52:54]:

Так. Начнем делать общую библиотеку, в нее вынесем все контракты, чтобы в любом микросервисе мы его соблюдали, на апишлюзе тоже поставим, и начнем с общей обертки для ответа фронту


```java
public class BaseResponse {
    public int status;
    public String message;

    public BaseResponse() {
    }

    public BaseResponse(int code, String message) {
        this.status = code;
        this.message = message;
    }
}

public class BaseResponse<T> extends BaseResponse {
    public T data;
}
```


вот такой контракт будет для общения с фронтом