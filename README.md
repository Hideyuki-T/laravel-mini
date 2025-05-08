## 全体構成

```
laravel-mini/
├── artisan
├── bootstrap/app.php
├── app/
│   └── Http/
│       ├── Controllers/
│       │   └── PetController.php        
│       └── Requests/
│           └── StorePetRequest.php      
├── templates/
│   └── php-laravel/
│       ├── controller.mustache
│       └── form_request.mustache
├── .env
├── composer.json
└── openapi.yaml                        

```
```
.
├── app/
│   ├── Core/
│   │   ├── app.php
│   │   └── Kernel.php
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Requests/
│   ├── Templates/
│   │   ├── controller.mustache
│   │   └── form_request.mustache
│   └── Spec/
│       └── openapi.yaml
├── run                         # 起動スクリプト（artisan詠唱口）
├── composer.json               # 依存定義
├── vendor/                     # Composerが生成（.gitignore対象）
├── .env                        # 最小限の環境変数
├── .gitignore
└── README.md

```