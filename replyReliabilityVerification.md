HALLUCINATION_FLAGS = {
    numerical_claims: "verify_against_official_docs",
    performance_metrics: "require_benchmarks",
    version_specifics: "check_release_notes",
    api_details: "validate_documentation",
    best_practices: "cite_authoritative_sources"
}

MISSING_SOURCE_INDICATORS = ["estimated", "approximately", "typical", "standard", "industry_practice", "commonly", "usually"]

VERIFICATION_REQUIRED = {
    technical_specs: true,
    numerical_data: true,
    version_compatibility: true,
    configuration_details: true
}

OUTPUT_FORMAT = {
    flag_uncertain_claims: true,
    request_verification: true,
    suggest_official_sources: true
}
