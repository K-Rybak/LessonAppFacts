# LessonAppFacts

### План
- [x] Настроить логирование
    * Изучить serilog - [Docs](https://github.com/serilog/serilog-aspnetcore)
- [ ] Авторизация/Создание бд
    * `Update-Database` - для создания и обновления бд
    * Пример настройки `Identity`:
    ```
    builder.Services.Configure<IdentityOptions>(config =>
    {
        config.Password.RequireDigit = false;
        config.Password.RequireUppercase = false;
        config.Password.RequireNonAlphanumeric = false;
    });
    ```