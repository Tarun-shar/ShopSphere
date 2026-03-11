🏗 Final Clean Architecture + MVVM Structure (ShopSphere)

data
│
├── remote
│   ├── api
│   │     ProductApi.kt
│   └── dto
│         ProductDto.kt
│
├── local
│   ├── dao
│   │     ProductDao.kt
│   ├── entity
│   │     ProductEntity.kt
│   └── database
│         ShopSphereDatabase.kt
│
├── paging
│     ProductPagingSource.kt
│
├── repository
│     ProductRepositoryImpl.kt
│
└── mapper
      ProductMapper.kt


domain
│
├── model
│     Product.kt
│
├── repository
│     ProductRepository.kt
│
└── usecase
      GetProductsUseCase.kt


presentation
│
├── screens
│   ├── product_list
│   │     ProductListScreen.kt
│   │     ProductListState.kt
│   │
│   ├── product_detail
│   │     ProductDetailScreen.kt
│   │
│   ├── cart
│   │     CartScreen.kt
│   │
│   ├── search
│   │     SearchScreen.kt
│   │
│   └── profile
│         ProfileScreen.kt
│
├── components
│     ProductCard.kt
│
└── viewmodel
      ProductViewModel.kt


di
│     NetworkModule.kt
│     DatabaseModule.kt
│     RepositoryModule.kt


utils
      Constants.kt
      Resource.kt


<img width="1599" height="899" alt="image" src="https://github.com/user-attachments/assets/21fa09a1-35f0-456e-b866-226ff417491a" />
