# Practica4Ismaelgithub.io
Diego Ismael Davila Castro
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amor en la Pantalla - Películas de Romance</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff0f5;
            color: #333;
        }
        
        header {
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            color: white;
            text-align: center;
            padding: 2rem 0;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .movie-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }
        
        .movie-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .movie-card:hover {
            transform: translateY(-10px);
        }
        
        .movie-poster {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }
        
        .movie-info {
            padding: 15px;
        }
        
        .movie-title {
            font-size: 1.2rem;
            margin: 0 0 5px 0;
            color: #d23669;
        }
        
        .movie-year {
            color: #888;
            font-size: 0.9rem;
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        .tagline {
            font-style: italic;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Amor en la Pantalla</h1>
            <p class="tagline">Las historias de amor más conmovedoras del cine</p>
        </div>
    </header>
    
    <div class="container">
        <h2>Películas Románticas Destacadas</h2>
        
        <div class="movie-grid">
            <!-- Película 1 -->
            <div class="movie-card">
                <img src="https://via.placeholder.com/300x450/ffb6c1/ffffff?text=Diario+de+una+pasion" alt="Diario de una pasión" class="movie-poster">
                <div class="movie-info">
                    <h3 class="movie-title">Diario de una pasión</h3>
                    <p class="movie-year">2004</p>
                    <p>La historia de Noah y Allie, un amor que supera todas las barreras.</p>
                </div>
            </div>
            
            <!-- Película 2 -->
            <div class="movie-card">
                <img src="https://via.placeholder.com/300x450/ffb6c1/ffffff?text=Antes+del+amanecer" alt="Antes del amanecer" class="movie-poster">
                <div class="movie-info">
                    <h3 class="movie-title">Antes del amanecer</h3>
                    <p class="movie-year">1995</p>
                    <p>Un encuentro casual en un tren se convierte en una noche mágica en Viena.</p>
                </div>
            </div>
            
            <!-- Película 3 -->
            <div class="movie-card">
                <img src="https://via.placeholder.com/300x450/ffb6c1/ffffff?text=El+mejor+de+mi" alt="El mejor de mi" class="movie-poster">
                <div class="movie-info">
                    <h3 class="movie-title">El mejor de mi</h3>
                    <p class="movie-year">2004</p>
                    <p>Dos almas destinadas a estar juntas a pesar de las circunstancias.</p>
                </div>
            </div>
            
            <!-- Película 4 -->
            <div class="movie-card">
                <img src="https://via.placeholder.com/300x450/ffb6c1/ffffff?text=La+la+land" alt="La la land" class="movie-poster">
                <div class="movie-info">
                    <h3 class="movie-title">La la land</h3>
                    <p class="movie-year">2016</p>
                    <p>Un musical moderno sobre sueños, amor y sacrificios en Los Ángeles.</p>
                </div>
            </div>
        </div>
    </div>
    
    <footer>
        <div class="container">
            <p>&copy; 2023 Amor en la Pantalla - Todos los derechos reservados</p>
            <p>Contacto: info@amorenlapantalla.com</p>
        </div>
    </footer>
</body>
</html>
