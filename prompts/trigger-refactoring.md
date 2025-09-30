Refactor the OpportunityTrigger into a Handler class. Move the validation and stage‑change logic into the appropriate bulkified methods. Update the trigger to delegate only and keep behavior identical. Deploy to the default org.

Write unit tests that covers each of the methods with positive and negative cases and includes a bulk test that updates 50 opportunities, where only half qualify for the after-update logic.

Deploy to the default org. Run these new unit tests and report coverage and details.