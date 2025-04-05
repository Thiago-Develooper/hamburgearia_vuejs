<template>
    <div id="burger-table">
        <div>
            <div id="burger-table-heading">
                <div class="order-id">#:</div>
                <div>Cliente:</div>
                <div>Pão:</div>
                <div>Carne:</div>
                <div>Opcionais:</div>
                <div>Ações:</div>
            </div>
        </div>
        <div id="burger-table-rows">
            <div class="burger-trable-rows">
                <div class="order-number">
                    <div>João</div>
                    <div>Pão de trigo</div>
                    <div>Maminha</div>
                    <div>
                        <ul>
                            <li>Salame</li>
                            <li>Tomate</li>
                        </ul>
                    </div>
                    <div>
                        <select name="" class="status">
                            <option value="">Selecione o status   do hamburguer</option>
                        </select>
                        <button class="delete-btn">Cancelar</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Dashboard"
    }
</script>

<script>

</script>