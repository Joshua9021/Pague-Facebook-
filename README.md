// Manejar intent inicial
handleIntent(getIntent());
// Observadores
viewModel.getNavigationEvent().observe(this, navTarget -> {
    // navegar o actualizar UI
});