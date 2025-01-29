<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venda sua Casa</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h3>Cadastre sua casa para vender mais rápido</h3>
        </div>
        <div class="form-container">
            <div class="form-header">
                <p>Formulário</p>
            </div>
            <div class="form-body">
               <h1 class="form-title">Venda fácil sua casa!</h1> 
               <p>
                Descreva as características e marque os opcionais que possui
               </p>
               <form>
                <div class="box-input">
                    <label for="title"
                        >Título do anúncio <span class="required-field">*</span></label
                    >
					<input
					type="text"
					name="title"
					id="title"
					class="block"
					placeholder="Um título para anunciar sua casa"
					minlength="1"
					maxlength="30"
					required
					/>
                </div>
				<div class="box-input">
                    <label for="price"
                        >Preço <span class="required-field">*</span></label
                    >
					<input
					type="number"
					name="price"
					id="price"
					class="block"
					placeholder="Defina o preço"
					required
					/>                              
                </div>
                <div class="box-input">
                    <label for="description"
                        >Descrição <span class="required-field">*</span></label
                    >
					<textarea name="description" id="description" class="block" placeholder="Aqui você coloca os detalhes da casa, por exemplo: se passou por reforma"
                    ></textarea>                         
                </div>
                <div class="box-input">
                    <label for="rooms"
                        >Quartos <span class="required-field">*</span></label
                    >
					<input
					type="text"
					name="rooms"
					id="rooms"
					class="block"
					placeholder="Digite quantos quartos tem"
					required
					/>                              
                </div>
                <div class="box-input">
                    <label for="wc"
                        >Banheiro <span class="required-field">*</span></label
                    >
					<input
					type="text"
					name="wc"
					id="wc"
					class="block"
					placeholder="Digite quantos banheiros tem"
					required
					/>                              
                </div>
                <div class="box-input">
                    <label for="vacancies"
                        >Vagas <span class="required-field">*</span></label
                    >
					<input
					type="number"
					name="vacancies"
					id="vacancies"
					class="block"
					placeholder="Digite a quantidade de vagas"
					required
					/>                              
                </div>
                <div class="box-input">
                    <label for="purchase_date"
                        >Data de compra <span class="required-field">*</span></label
                    >
					<input
					type="date"
					name="purchase_date"
					id="purchase_date"
					class="block"
					required
					/>                              
                </div>
                <div class="box-input">
                    <p>Tipo de cozinha: <span class="required-field">*</span></p>
					<input type="radio" id="linear" name="gear">
                    <label for="linear">Linear</label>
                    <input type="radio" id="american" name="gear">
                    <label for="american">Americana</label>                             
                </div>
                <div class="optional-box">
                    <p>Opcionais</p>
					<ul class="optional-list">
                        <li>
                            <input 
                            type="checkbox" 
                            id="barbecue" 
                            name="optional[]" 
                            value="barbecue"
                            />
                            <label for="barbecue">Churrasqueira</label>
                        </li>
                        <li>
                            <input 
                            type="checkbox" 
                            id="pets" 
                            name="optional[]" 
                            value="pets"
                            />
                            <label for="pets">Aceita Animais</label>
                        </li>
                        <li>
                            <input 
                            type="checkbox" 
                            id="ac" 
                            name="optional[]" 
                            value="ac"
                            />
                            <label for="ac">Ar Condicionado</label>
                        </li>
                        <li>
                            <input 
                            type="checkbox" 
                            id="furnished" 
                            name="optional[]" 
                            value="furnished"
                            />
                            <label for="furnished">Mobiliado</label>
                        </li>
                    </ul>                        
                </div>
                <div class="optional-box">
					<ul class="optional-list">
                        <li>
                            <input 
                            type="checkbox" 
                            id="gourmet_space" 
                            name="optional[]" 
                            value="gourmet_space"
                            />
                            <label for="gourmet_space">Espaço Gourmet</label>
                        </li>
                        <li>
                            <input 
                            type="checkbox" 
                            id="swimming_pool 
                            name="optional[]" 
                            value="keyl"
                            />
                            <label for="swimming_pool">Piscina</label>
                        </li>
                        <li>
                            <input 
                            type="checkbox" 
                            id="electronic_gate" 
                            name="optional[]" 
                            value="electronic_gate"
                            />
                            <label for="electronic_gate">Portão Eletrônico</label>
                        </li>
                        <li>
                            <input 
                            type="checkbox" 
                            id="office" 
                            name="optional[]" 
                            value="office"
                            />
                            <label for="office">Escritório</label>
                        </li>
                    </ul>                        
                </div>
                <div class="box-input">
                    <p>Fotos da casa: <span class="required-field">*</span></p>
                    <input type="file" multiple accept="image/png, image/jpg"
                    id="images"
                    name="images"
                    required
                    />
                </div>
                   <input type="submit" value="Enviar" class="btn-submit"/>
               </form>
            </div>
        </div>
    </div>
</body>
</html>
