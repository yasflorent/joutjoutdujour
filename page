<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Vídeo Aleatório da Jout Jout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
            margin: 0;
        }

        .container {
            text-align: center;
        }

        iframe {
            width: 100%;
            max-width: 560px;
            height: 315px;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        p {
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Vídeo do Dia - Jout Jout</h1>
        <iframe id="video" src="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <p>Assistindo: <span id="videoTitle"></span></p>
    </div>

    <script>
        // Lista de vídeos do canal da Jout Jout (IDs do YouTube)
        const videos = [
            { id: 'dQw4w9WgXcQ', title: 'Vídeo 1' },
            { id: 'C0DPdy98e4c', title: 'Vídeo 2' },
            { id: 'tVlcKp3bWH8', title: 'Vídeo 3' },
            // Adicione mais vídeos aqui com o formato {id: 'youtube_video_id', title: 'Título do Vídeo'}
        ];

        // Função para gerar um vídeo aleatório com base na data do dia
        function getRandomVideo() {
            const date = new Date();
            const day = date.getDate();
            const randomIndex = day % videos.length; // Gera um índice baseado no dia do mês
            return videos[randomIndex];
        }

        // Definir o vídeo na página
        const video = getRandomVideo();
        document.getElementById('video').src = `https://www.youtube.com/embed/${video.id}`;
        document.getElementById('videoTitle').innerText = video.title;
    </script>
</body>
</html>
