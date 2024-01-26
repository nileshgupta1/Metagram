
# Metagram

An innovative social media app crafted with React and Node.js, with exceptional user interface/experience. Seamlessly blending  design with functionality, the platform offers users a visually captivating and navigable space for meaningful connections and engaging interactions.



## Demo

![Screenshot (751)](https://github.com/nileshgupta1/Metagram/assets/117779500/c56e6b91-0714-4280-ad59-19ab0a2085e6)
![Screenshot (752)](https://github.com/nileshgupta1/Metagram/assets/117779500/46ed4757-e546-4cfd-a3e8-d7ad10bba1fa)
![Screenshot (753)](https://github.com/nileshgupta1/Metagram/assets/117779500/27d1a6bf-a704-44e4-9e35-c49bf1dd69c3)
![Screenshot (754)](https://github.com/nileshgupta1/Metagram/assets/117779500/01c74be4-beb1-4318-a88e-66714d914fa4)


## API Reference

#### Get all timeline posts

```http
  GET /post/${user_id}/timeline
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `user_id` | `string` | **Required** user's Id |

#### Get individual post

```http
  GET /post/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required** Id of post to fetch |

#### Create a post

```http
  POST /post/
```

 | Description                       |
 :-------------------------------- |
 | **Required** body of the post |



