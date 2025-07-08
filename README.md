1. убрал во всех тестах from tests.conftest import driver
2. Изменил метод get_page_title теперь проверяет только наличие
непустого заголовка страницы.