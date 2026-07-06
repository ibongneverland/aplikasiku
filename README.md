# Aplikasiku

**Laravel 12**

## Tips
1. 1071 Specified key was too long
    - Tambahkan `use Illuminate\Support\Facades\Schema;` pada `AppServiceProvider.php`
    - Tambahkan `Schema::defaultStringLength(191);` pada `boot()` method
    - Untuk proses migrasi pertama kali, gunakan `php artisan migrate:fresh`
    - Untuk proses migrasi selanjutnya, gunakan `php artisan migrate`

## Branch
### main
- Aplikasiku
- Laravel 12
- Livewire
- MySQL

### template
- Aplikasiku
- Laravel 12
- SQLite


## 2026.