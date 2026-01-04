/_ ==========================================
Animación suave al aparecer
========================================== _/
.section,
.project-card,
.blog-card,
.skills-block {
opacity: 0;
transform: translateY(20px);
transition: all 0.6s ease;
}

.visible {
opacity: 1;
transform: translateY(0);
}

/_ ==========================================
Efecto del header al hacer scroll
========================================== _/
.header--scrolled {
background: rgba(2,6,23,0.85);
border-bottom: 1px solid rgba(56,189,248,0.2);
backdrop-filter: blur(14px);
}
