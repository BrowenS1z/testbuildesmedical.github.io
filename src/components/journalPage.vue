<template>
    <div class="wrapper-journal">
        <form class="d-flex form-search">
            <input class="form-control me-2" type="search" placeholder="Введите текст для поиска" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Найти</button>
        </form>
        <div class="content-table">
            <table class="table">
                <thead>
                    <tr>
                        <th scope="col">Дата выдачи</th>
                        <th scope="col">Серия справки</th>
                        <th scope="col">Номер справки</th>
                        <th scope="col">ФИО освидетельствуемого</th>
                        <th scope="col">Дата рождения освидетельствуемого</th>
                        <th scope="col">Наличие (отсутствие) медицинских противопоказаний</th>
                        <th scope="col">Наличие (отсутствие) медицинских ограничений</th>
                        <th scope="col">Наличие (отсутствие) медицинских показаний</th>
                        <th scope="col"></th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                        <td>8</td>
                        <td><button type="button" class="btn btn-success">Edit</button></td>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>2</td>
                        <td>3</td>
                        <td>4</td>
                        <td>5</td>
                        <td>6</td>
                        <td>7</td>
                        <td>8</td>
                        <td><button type="button" class="btn btn-success">Edit</button></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

<script>

</script>

<style>
.wrapper-journal{
    margin-top: 10px;
}

.form-search{
    width: 340px;
    float: right;
    margin-right: 40px;
    margin-bottom: 30px;
}

.content-table{
    padding: 0 40px 0 40px;
}
</style>
