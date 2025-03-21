<!-- Sección Principal -->
<div class="main-content">
    <div class="bio">
        <h2>Biografía</h2>
        <p>Ingeniera en Logística y Transporte graduada de la Universidad Politécnica Estatal del Carchi, con sólida formación en gestión logística, análisis de datos, y manejo de KPIs. Experta en herramientas analíticas como Power BI y en la implementación de software ERP, como Odoo, entre otros, para optimizar procesos y mejorar la eficiencia operativa. Proactiva, con habilidades en trabajo en equipo y resolución de problemas. ...</p>
    </div>
    <div class="interests">
        <h2>Intereses Profesionales</h2>
        <ul>
            <li>Logística y Cadena de Suministro </li>
            <li>Transporte y Operaciones</li>
            <li>Gestión de Compras y Abastecimiento</li>
            <li>Consultoría en optimización de procesos logísticos y operativos</li>
            <li>Logística para eventos y conciertos </li>
            <li>Gestión de inventario y transporte en producciones Audiovisuales.</li>
            <li>Automatización y Digitalización Logística</li>
        </ul>
    </div>

    <div class="portfolio">
        <h2>Portafolio de Proyectos</h2>
        <div class="tabs">
            <div class="tab-btn" onclick="showTab('consultoria', this)">Proyectos Consultoría</div>
            <div class="tab-btn" onclick="showTab('investigacion', this)">Proyectos Investigación</div>
            <div class="tab-btn" onclick="showTab('cursos', this)">Cursos</div>
            <div class="tab-btn" onclick="showTab('colaboraciones', this)">Colaboraciones</div>
        </div>

        <div id="consultoria" class="tab-content active">
            <div class="year" onclick="toggleYear('y2023')">2023</div>
            <div id="y2023" class="year-content">Contenido del año 2023...</div>
        </div>
        <div id="investigacion" class="tab-content">Contenido de investigación...</div>
        <div id="cursos" class="tab-content">Contenido de cursos...</div>
        <div id="colaboraciones" class="tab-content">Contenido de colaboraciones...</div>
    </div>
</div>
