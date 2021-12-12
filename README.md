# MotdParser
A project that can be used to parse minecraft motds

# Usage
```csharp
MCMotd motd = new MCMotd(
    "{\"description\":{\"text\":\"§4⬟⬠§6⬟⬠§2⬟⬠§3⬟⬠§9⬟⬠§d⬟⬠§f§l  Holycube§c§l ⑤§d   ⬟⬠§9⬟⬠§3⬟⬠§2⬟⬠§6⬟⬠§4⬟⬠§r\\n§4~§c~§6~§e~§2~§a~§b~§3~§9~§1~§d~§5~§a§lwww.holycube.fr§5~§d~§1~§9~§3~§b~§a~§2~§e~§6~§c~§4~\"},\"players\":{\"max\":42,\"online\":10,\"sample\":[{\"id\":\"36f8a77e-cfe5-4c6f-af63-008a6cfee733\",\"name\":\"OraNN_\"},{\"id\":\"38cb109f-b47b-452e-b32d-0eb9e3cbf62a\",\"name\":\"OraNNa\"},{\"id\":\"2d14c120-9f2b-4ca0-ae91-5bf8329c147f\",\"name\":\"Reyza_Sama\"},{\"id\":\"868342e2-4f6a-45a7-a409-b0dc7dabf16a\",\"name\":\"Mayukow\"},{\"id\":\"79c93539-3f74-4e20-9906-f083cb77185e\",\"name\":\"Goldawn\"},{\"id\":\"651b005e-bc53-4a74-b516-a9cecd2ad6f4\",\"name\":\"tungstene74\"},{\"id\":\"ec34ef76-3ca6-4cd4-9572-93711dfe385f\",\"name\":\"ShoukaSeikyo\"},{\"id\":\"c59220b1-662f-4aa8-b9d9-72660eb97c10\",\"name\":\"Aurelien_Sama\"},{\"id\":\"dc601ba5-3143-49b1-8db2-aaa7343fe14d\",\"name\":\"MrMLDEG\"},{\"id\":\"23fcbba9-328d-4216-886b-0dfabf303bd2\",\"name\":\"Zanzag\"}]},\"version\":{\"name\":\"1.16.4\",\"protocol\":754},\"favicon\":\"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAQAAAAAYLlVAAAEiklEQVR42u2Za2wUVRTHx5ZXoVK0lhgBwRegLRhfsQgRo/VVYghRgvaDqVYL0Q+KCCEYI37QGDUaQ9XgB4xgMMbEaHwEeQSMGjQRK7alRuWhUkSkQHnTZfvj39lm9l72McNuZzdqz0lmd+fMvfd/z9x7zv/cdZw++fcKPWp+yzWAQmqYqs8LqKMkHwAKeJ+39FnNd5RmCIDzMtYyBvA8qwTjET5hsCCUnXkvDpsy1kbup1bXYbzIEirZmEkvDndmrNO4lJv5lfGsZJ5mk1Ev2a6CcQIwjbXcTZ42YqncuEjOvzZfAAbwKZ8JwEjyFoqWEGUDQ/IHYCarWaitmLdwXEB/RUQH578imksxFUz09FxMWxHlnuVKRiTOXHfO4nxu4zFe4DVeYj7TuajbR8EBTKWNdva62q5oZ9omstWzHeBlG4C7JkbyDM0cIy6dbKNBkwr2mvRYldX8YQvAVewzbG+anbrDV/ItXSST37hHvgkPgDv8BJpILX8rZvp7IQsAg5Wc08v3AQJWZgDc+d/BYR8AXcz19UEWAN6wBtvDMu2AxYqSEePueu2xkACcIwfHpZ0Z3dHRvf+2tQ4qwgIwnt2GZSX9PMs1/GNsybvCAjDZWgHzLN9sSt5f7wK4leOG5UFrd3xpWOaGBeB2ThiWBzDD9wbbN7kG0I9ZLOBJV+dzXY4BZJIN+wD0AZikcmuLpzMDApjCj0arGcEZUFmCjhDtqvD0QrcMjemQBACFbkma2GqU0SqtOrQKb7OnLe6vJn029VybdafFtf3MK6qATACvcxnfyJq6VUtP2+S6hVZHHM/s8qT4YESlRpvSRuzaxS7v7X6gMGIDmKC8h1q0qWWsrdmDn+xlm8Nwsde47KdOTQ8xmz84why2a0HW84sPgN1q1U1V68UC9uv6Fx08xJ++AJ5meCyNLPVS6RGWi+12UMMOfa9R7RthhbJ4egAdvKOn93Cv+tmn607BXm49mSg7RWBupGcFD9WbjBps9gTrOKih16lrU95LASAmR1WmH1VOXGsl5oh6S9Qoa5SkjHRRKacf8HHYxxruagtAg+qE9PPs5CkVKYkHE9VcbxUrAnGxkDeyWa5MpJJbRSk2K5edHgcaGKtUm7zVce2FH1QlTApajhRSwjBGq7vTJaK1UCxeU5QkEBWkbLWdK1xbf84oCg5S6H3X4rGf8yyXkyYSSgdSq2V40rB8qB10Nr2SC+qzJiQFoqVV3OJqlbyVcwBFrJZPj7nayeP5AJAVJ+wNAOtzAcCm5XUpaXlor+AGZZC4LDAspWIKSaD1NoCxyprmNhzo/ZMwWQkqHuSrw6LlJYp6cTmo0F7knheN4SPj/i7VkKGV569akfCwQvtS5cRW68jmC62I0ADc5JvOooqP4RxQOLGAvMwHwFeiP6EeUl3CxjTD73D/Xwr5mK6cVVZSikuj+nWCHdNNEQf83dP7rCHK+UlsMWZp47kkB5WlPMrX2nhRj00cUhxYrN0Q+KBykGqB0Z4WY/8/MMqzjOk+xiXZCfpQ0fcanmChSEytJlQW6IiyT/6ncgqDHKOqLrLgrAAAAABJRU5ErkJggg\\u003d\\u003d\"}"
    );

Console.WriteLine(motd.Colorized());
```
