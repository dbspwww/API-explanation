# content 전체 조회 API

## /api/boards

### requset

- METHOD : GET
- parameter : none

---

### headers

- 'Content-Type': 'application/json'

### Request body

없음

---

### Response

#### 성공

```
[
    {
    'id' : 'number',
    'title : 'string',
    'sub_title' : 'string',
    'uptime' : 'string',
    'name': 'string'
    }, ...
]
```

#### 실패

```
{
    status: 500
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```
