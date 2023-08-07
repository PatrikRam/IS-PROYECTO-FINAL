<script>
</script>

<section class="event-publish-section">
  <h2>Publicar un Evento</h2>
  <form id="event-form" method="POST">
    <div class="form-group">
      <label for="event-title">Título del Evento:</label>
      <input type="text" id="event-title" required />
    </div>

    <div class="form-group">
      <label for="event-date">Fecha del Evento:</label>
      <input type="date" id="event-date" required />
    </div>

    <div class="form-group">
      <label for="event-description">Descripción:</label>
      <textarea id="event-description" rows="4" required></textarea>
    </div>

    <button type="submit">Publicar Evento</button>
  </form>
</section>

<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }

  .event-publish-section {
    padding: 2rem;
    background-color: #f9f9f9;
  }

  h2 {
    border-bottom: 2px solid #333;
    padding-bottom: 0.5rem;
    color: #333;
    font-size: 24px;
    margin-bottom: 1.5rem;
  }

  .form-group {
    margin-bottom: 1.5rem;
  }

  label {
    display: block;
    font-size: 18px;
    color: #333;
    font-weight: bold;
    margin-bottom: 0.5rem;
  }

  input,
  textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 16px;
    color: #333;
    box-sizing: border-box;
  }

  textarea {
    resize: vertical;
  }

  button {
    background-color: #195c29;
    color: #fff;
    padding: 12px;
    border: none;
    cursor: pointer;
    font-size: 18px;
    font-weight: bold;
    text-transform: uppercase;
    border-radius: 4px;
    transition: background-color 0.3s ease;
  }

  button:hover {
    background-color: #226b34;
  }
</style>
