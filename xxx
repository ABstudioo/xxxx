// <copyright file="BingSearchResult.cs" company="Microsoft">
// Copyright (c) Microsoft. All rights reserved.
// </copyright>

namespace Microsoft.Teams.Apps.CompanyCommunicator.Bot
{
    using System.Collections.Generic;
    using Microsoft.Bot.Schema;

    /// <summary>
    /// The Bing search result class.
    /// </summary>
    public class BingSearchResult : IBingSearchResult
    {
        /// <summary>
        /// Gets or sets the query context.
        /// </summary>
        public QueryContext QueryContext { get; set; }

        /// <summary>
        /// Gets or sets the search results.
        /// </summary>
        public List<SearchResult> SearchResults { get; set; }
    }
}

public async Task<IBingSearchResult> SearchAsync(string query)
{
    // Implement your Bing search logic here...

    // Create an instance of the BingSearchResult class...
    var result = new BingSearchResult
    {
        QueryContext = new QueryContext { OriginalQuery = query },
        SearchResults = new List<SearchResult>(), // Populate this list with the actual search results...
    };

    return result;
}

    private async void btnLoadEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var events = await dbContext.Events.ToListAsync();
            lstEvents.DataSource = events;
        }
    }

    private async void btnLoadUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var users = await dbContext.Users.ToListAsync();
            lstUsers.DataSource = users;
        }
    }

    private async void btnLoadPartners_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partners = await dbContext.Partners.ToListAsync();
            lstPartners.DataSource = partners;
        }
    }

    private async void btnLoadPartnerUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUsers = await dbContext.PartnerUsers.ToListAsync();
            lstPartnerUsers.DataSource = partnerUsers;
        }
    }

    private async void btnLoadPartnerRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequests = await dbContext.PartnerRequests.ToListAsync();
            lstPartnerRequests.DataSource = partnerRequests;
        }
    }

    private async void btnLoadPartnerLocations_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerLocations = await dbContext.PartnerLocations.ToListAsync();
            lstPartnerLocations.DataSource = partnerLocations;
        }
    }

    private async void btnLoadEventMedia_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventMedia = await dbContext.EventMedias.ToListAsync();
            lstEventMedia.DataSource = eventMedia;
        }
    }

    private async void btnLoadUserNotifications_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userNotifications = await dbContext.UserNotifications.ToListAsync();
            lstUserNotifications.DataSource = userNotifications;
        }
    }

    private async void btnLoadNotifications_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var notifications = await dbContext.Notifications.ToListAsync();
            lstNotifications.DataSource = notifications;
        }
    }

    private async void btnLoadPartnerUserNotifications_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserNotifications = await dbContext.PartnerUserNotifications.ToListAsync();
            lstPartnerUserNotifications.DataSource = partnerUserNotifications;
        }
    }

    private async void btnLoadSiteMetrics_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var siteMetrics = await dbContext.SiteMetrics.ToListAsync();
            lstSiteMetrics.DataSource = siteMetrics;
        }
    }

    private async void btnLoadSites_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var sites = await dbContext.Sites.ToListAsync();
            lstSites.DataSource = sites;
        }
    }

    private async void btnLoadContactRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var contactRequests = await dbContext.ContactRequests.ToListAsync();
            lstContactRequests.DataSource = contactRequests;
        }
    }

    private async void btnLoadRequestedSites_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var requestedSites = await dbContext.RequestedSites.ToListAsync();
            lstRequestedSites.DataSource = requestedSites;
        }
    }

    private async void btnLoadComments_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var comments = await dbContext.Comments.ToListAsync();
            lstComments.DataSource = comments;
        }
    }

    private async void btnLoadWaiverDuration_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var waiverDuration = await dbContext.WaiverDurationTypes.ToListAsync();
            lstWaiverDuration.DataSource = waiverDuration;
        }
    }

    private async void btnLoadEventStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventStatus = await dbContext.EventStatus.ToListAsync();
            lstEventStatus.DataSource = eventStatus;
        }
    }

    private async void btnLoadEventType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventType = await dbContext.EventTypes.ToListAsync();
            lstEventType.DataSource = eventType;
        }
    }

    private async void btnLoadCancellationReason_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var cancellationReason = await dbContext.CancellationReasons.ToListAsync();
            lstCancellationReason.DataSource = cancellationReason;
        }
    }

    private async void btnLoadUserNotificationType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userNotificationType = await dbContext.UserNotificationTypes.ToListAsync();
            lstUserNotificationType.DataSource = userNotificationType;
        }
    }

    private async void btnLoadEventHistory_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventHistory = await dbContext.EventHistory.ToListAsync();
            lstEventHistory.DataSource = eventHistory;
        }
    }

    private async void btnLoadMediaType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var mediaType = await dbContext.MediaTypes.ToListAsync();
            lstMediaType.DataSource = mediaType;
        }
    }

    private async void btnLoadUserEventType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userEventType = await dbContext.UserEventTypes.ToListAsync();
            lstUserEventType.DataSource = userEventType;
        }
    }

    private async void btnLoadUserRoleType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userRoleType = await dbContext.UserRoleTypes.ToListAsync();
            lstUserRoleType.DataSource = userRoleType;
        }
    }

    private async void btnLoadUserStatusType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userStatusType = await dbContext.UserStatusTypes.ToListAsync();
            lstUserStatusType.DataSource = userStatusType;
        }
    }

    private async void btnLoadUserType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userType = await dbContext.UserTypes.ToListAsync();
            lstUserType.DataSource = userType;
        }
    }

    private async void btnLoadPrivacyNotice_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var privacyNotice = await dbContext.PrivacyNotices.ToListAsync();
            lstPrivacyNotice.DataSource = privacyNotice;
        }
    }

    private async void btnLoadMeetup_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var meetup = await dbContext.Meetups.ToListAsync();
            lstMeetup.DataSource = meetup;
        }
    }

    private async void btnLoadMembershipType_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var membershipType = await dbContext.MembershipTypes.ToListAsync();
            lstMembershipType.DataSource = membershipType;
        }
    }

    private async void btnLoadSiteAdmins_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var siteAdmins = await dbContext.SiteAdmins.ToListAsync();
            lstSiteAdmins.DataSource = siteAdmins;
        }
    }

    private async void btnLoadUserSite_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userSite = await dbContext.UserSites.ToListAsync();
            lstUserSite.DataSource = userSite;
        }
    }

    private async void btnLoadMembershipUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var membershipUsers = await dbContext.MembershipUsers.ToListAsync();
            lstMembershipUsers.DataSource = membershipUsers;
        }
    }

    private async void btnLoadEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var events = await dbContext.Events.ToListAsync();
            lstEvents.DataSource = events;
        }
    }

    private async void btnLoadEventAttendees_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventAttendees = await dbContext.EventAttendees.ToListAsync();
            lstEventAttendees.DataSource = eventAttendees;
        }
    }

    private async void btnLoadEventMedias_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventMedias = await dbContext.EventMedias.ToListAsync();
            lstEventMedias.DataSource = eventMedias;
        }
    }

    private async void btnLoadUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var users = await dbContext.Users.ToListAsync();
            lstUsers.DataSource = users;
        }
    }

    private async void btnLoadNotifications_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var notifications = await dbContext.Notifications.ToListAsync();
            lstNotifications.DataSource = notifications;
        }
    }

    private async void btnLoadWasteTransferRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var wasteTransferRequests = await dbContext.WasteTransferRequests.ToListAsync();
            lstWasteTransferRequests.DataSource = wasteTransferRequests;
        }
    }

    private async void btnLoadPartnerUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUsers = await dbContext.PartnerUsers.ToListAsync();
            lstPartnerUsers.DataSource = partnerUsers;
        }
    }

    private async void btnLoadPartnerRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequests = await dbContext.PartnerRequests.ToListAsync();
            lstPartnerRequests.DataSource = partnerRequests;
        }
    }

    private async void btnLoadPartnerStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerStatus = await dbContext.PartnerStatus.ToListAsync();
            lstPartnerStatus.DataSource = partnerStatus;
        }
    }

    private async void btnLoadPartnerLocation_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerLocation = await dbContext.PartnerLocations.ToListAsync();
            lstPartnerLocation.DataSource = partnerLocation;
        }
    }

    private async void btnLoadPartners_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partners = await dbContext.Partners.ToListAsync();
            lstPartners.DataSource = partners;
        }
    }

    private async void btnLoadSuggestionStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var suggestionStatus = await dbContext.SuggestionStatus.ToListAsync();
            lstSuggestionStatus.DataSource = suggestionStatus;
        }
    }

    private async void btnLoadSuggestions_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var suggestions = await dbContext.Suggestions.ToListAsync();
            lstSuggestions.DataSource = suggestions;
        }
    }

    private async void btnLoadRequestors_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var requestors = await dbContext.Requestors.ToListAsync();
            lstRequestors.DataSource = requestors;
        }
    }

    private async void btnLoadBulkRequestStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkRequestStatus = await dbContext.BulkRequestStatus.ToListAsync();
            lstBulkRequestStatus.DataSource = bulkRequestStatus;
        }
    }

    private async void btnLoadBulkRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkRequests = await dbContext.BulkRequests.ToListAsync();
            lstBulkRequests.DataSource = bulkRequests;
        }
    }

    private async void btnLoadBulkPickupRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkPickupRequests = await dbContext.BulkPickupRequests.ToListAsync();
            lstBulkPickupRequests.DataSource = bulkPickupRequests;
        }
    }

    private async void btnLoadBulkPickupSites_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkPickupSites = await dbContext.BulkPickupSites.ToListAsync();
            lstBulkPickupSites.DataSource = bulkPickupSites;
        }
    }

    private async void btnLoadBulkPickupEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkPickupEvents = await dbContext.BulkPickupEvents.ToListAsync();
            lstBulkPickupEvents.DataSource = bulkPickupEvents;
        }
    }

    private async void btnLoadBulkPickupDates_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkPickupDates = await dbContext.BulkPickupDates.ToListAsync();
            lstBulkPickupDates.DataSource = bulkPickupDates;
        }
    }

    private async void btnLoadBulkPickupLocations_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var bulkPickupLocations = await dbContext.BulkPickupLocations.ToListAsync();
            lstBulkPickupLocations.DataSource = bulkPickupLocations;
        }
    }

    private async void btnLoadEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var events = await dbContext.Events.ToListAsync();
            lstEvents.DataSource = events;
        }
    }

    private async void btnLoadEventStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventStatus = await dbContext.EventStatus.ToListAsync();
            lstEventStatus.DataSource = eventStatus;
        }
    }

    private async void btnLoadEventAttendees_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventAttendees = await dbContext.EventAttendees.ToListAsync();
            lstEventAttendees.DataSource = eventAttendees;
        }
    }

    private async void btnLoadEventPartners_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventPartners = await dbContext.EventPartners.ToListAsync();
            lstEventPartners.DataSource = eventPartners;
        }
    }

    private async void btnLoadEventHistory_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventHistory = await dbContext.EventHistory.ToListAsync();
            lstEventHistory.DataSource = eventHistory;
        }
    }

    private async void btnLoadEventMedias_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventMedias = await dbContext.EventMedias.ToListAsync();
            lstEventMedias.DataSource = eventMedias;
        }
    }

    private async void btnLoadMediaPartners_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var mediaPartners = await dbContext.MediaPartners.ToListAsync();
            lstMediaPartners.DataSource = mediaPartners;
        }
    }

    private async void btnLoadMediaTypes_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var mediaTypes = await dbContext.MediaTypes.ToListAsync();
            lstMediaTypes.DataSource = mediaTypes;
        }
    }

    private async void btnLoadPartnerRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequests = await dbContext.PartnerRequests.ToListAsync();
            lstPartnerRequests.DataSource = partnerRequests;
        }
    }

    private async void btnLoadPartnerRequestStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestStatus = await dbContext.PartnerRequestStatus.ToListAsync();
            lstPartnerRequestStatus.DataSource = partnerRequestStatus;
        }
    }

    private async void btnLoadPartnerUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUsers = await dbContext.PartnerUsers.ToListAsync();
            lstPartnerUsers.DataSource = partnerUsers;
        }
    }

    private async void btnLoadPartnerLocations_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerLocations = await dbContext.PartnerLocations.ToListAsync();
            lstPartnerLocations.DataSource = partnerLocations;
        }
    }

    private async void btnLoadPartnerStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerStatus = await dbContext.PartnerStatus.ToListAsync();
            lstPartnerStatus.DataSource = partnerStatus;
        }
    }

    private async void btnLoadPartnerUserNotificationPreferences_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserNotificationPreferences = await dbContext.PartnerUserNotificationPreferences.ToListAsync();
            lstPartnerUserNotificationPreferences.DataSource = partnerUserNotificationPreferences;
        }
    }

    private async void btnLoadSiteMetrics_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var siteMetrics = await dbContext.SiteMetrics.ToListAsync();
            lstSiteMetrics.DataSource = siteMetrics;
        }
    }

    private async void btnLoadSiteMetricTypes_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var siteMetricTypes = await dbContext.SiteMetricTypes.ToListAsync();
            lstSiteMetricTypes.DataSource = siteMetricTypes;
        }
    }

    private async void btnLoadUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var users = await dbContext.Users.ToListAsync();
            lstUsers.DataSource = users;
        }
    }

    private async void btnLoadUserNotificationPreferences_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userNotificationPreferences = await dbContext.UserNotificationPreferences.ToListAsync();
            lstUserNotificationPreferences.DataSource = userNotificationPreferences;
        }
    }

    private async void btnLoadWaiverRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var waiverRequests = await dbContext.WaiverRequests.ToListAsync();
            lstWaiverRequests.DataSource = waiverRequests;
        }
    }

    private async void btnLoadWaiverRequestStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var waiverRequestStatus = await dbContext.WaiverRequestStatus.ToListAsync();
            lstWaiverRequestStatus.DataSource = waiverRequestStatus;
        }
    }

    private async void btnLoadUserEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userEvents = await dbContext.UserEvents.ToListAsync();
            lstUserEvents.DataSource = userEvents;
        }
    }

    private async void btnLoadEventAttendees_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventAttendees = await dbContext.EventAttendees.ToListAsync();
            lstEventAttendees.DataSource = eventAttendees;
        }
    }

    private async void btnLoadUserNotifications_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userNotifications = await dbContext.UserNotifications.ToListAsync();
            lstUserNotifications.DataSource = userNotifications;
        }
    }

    private async void btnLoadEventMedias_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventMedias = await dbContext.EventMedias.ToListAsync();
            lstEventMedias.DataSource = eventMedias;
        }
    }

    private async void btnLoadEventStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventStatus = await dbContext.EventStatus.ToListAsync();
            lstEventStatus.DataSource = eventStatus;
        }
    }

    private async void btnLoadEventHistory_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventHistory = await dbContext.EventHistory.ToListAsync();
            lstEventHistory.DataSource = eventHistory;
        }
    }

    private async void btnLoadEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var events = await dbContext.Events.ToListAsync();
            lstEvents.DataSource = events;
        }
    }

    private async void btnLoadUserHistory_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userHistory = await dbContext.UserHistory.ToListAsync();
            lstUserHistory.DataSource = userHistory;
        }
    }

    private async void btnLoadSiteMaps_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var siteMaps = await dbContext.SiteMaps.ToListAsync();
            lstSiteMaps.DataSource = siteMaps;
        }
    }

    private async void btnLoadRequestors_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var requestors = await dbContext.Requestors.ToListAsync();
            lstRequestors.DataSource = requestors;
        }
    }

    private async void btnLoadMediaRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var mediaRequests = await dbContext.MediaRequests.ToListAsync();
            lstMediaRequests.DataSource = mediaRequests;
        }
    }

    private async void btnLoadMediaTypes_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var mediaTypes = await dbContext.MediaTypes.ToListAsync();
            lstMediaTypes.DataSource = mediaTypes;
        }
    }

    private async void btnLoadEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var eventsSummary = await dbContext.EventsSummary.ToListAsync();
            lstEventsSummary.DataSource = eventsSummary;
        }
    }

    private async void btnLoadUserNotificationsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userNotificationsSummary = await dbContext.UserNotificationsSummary.ToListAsync();
            lstUserNotificationsSummary.DataSource = userNotificationsSummary;
        }
    }

    private async void btnLoadUserDatesSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var userDatesSummary = await dbContext.UserDatesSummary.ToListAsync();
            lstUserDatesSummary.DataSource = userDatesSummary;
        }
    }

    private async void btnLoadUsersSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var usersSummary = await dbContext.UsersSummary.ToListAsync();
            lstUsersSummary.DataSource = usersSummary;
        }
    }

    private async void btnLoadSiteSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var siteSummary = await dbContext.SiteSummary.ToListAsync();
            lstSiteSummary.DataSource = siteSummary;
        }
    }

    private async void btnLoadPickupEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var pickupEvents = await dbContext.PickupEvents.ToListAsync();
            lstPickupEvents.DataSource = pickupEvents;
        }
    }

    private async void btnLoadPickupEventMedias_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var pickupEventMedias = await dbContext.PickupEventMedias.ToListAsync();
            lstPickupEventMedias.DataSource = pickupEventMedias;
        }
    }

    private async void btnLoadPickupEventHistory_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var pickupEventHistory = await dbContext.PickupEventHistory.ToListAsync();
            lstPickupEventHistory.DataSource = pickupEventHistory;
        }
    }

    private async void btnLoadPickupRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var pickupRequests = await dbContext.PickupRequests.ToListAsync();
            lstPickupRequests.DataSource = pickupRequests;
        }
    }

    private async void btnLoadPartnerStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerStatus = await dbContext.PartnerStatus.ToListAsync();
            lstPartnerStatus.DataSource = partnerStatus;
        }
    }

    private async void btnLoadPartnerRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequests = await dbContext.PartnerRequests.ToListAsync();
            lstPartnerRequests.DataSource = partnerRequests;
        }
    }

    private async void btnLoadPartnerLocations_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerLocations = await dbContext.PartnerLocations.ToListAsync();
            lstPartnerLocations.DataSource = partnerLocations;
        }
    }

    private async void btnLoadPartnerUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUsers = await dbContext.PartnerUsers.ToListAsync();
            lstPartnerUsers.DataSource = partnerUsers;
        }
    }

    private async void btnLoadPartnerEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEvents = await dbContext.PartnerEvents.ToListAsync();
            lstPartnerEvents.DataSource = partnerEvents;
        }
    }

    private async void btnLoadPartnerUsersSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUsersSummary = await dbContext.PartnerUsersSummary.ToListAsync();
            lstPartnerUsersSummary.DataSource = partnerUsersSummary;
        }
    }

    private async void btnLoadPartnerEventSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventSummary = await dbContext.PartnerEventSummary.ToListAsync();
            lstPartnerEventSummary.DataSource = partnerEventSummary;
        }
    }

    private async void btnLoadPartnerEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsSummary = await dbContext.PartnerEventsSummary.ToListAsync();
            lstPartnerEventsSummary.DataSource = partnerEventsSummary;
        }
    }

    private async void btnLoadPartnerEventsHistory_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsHistory = await dbContext.PartnerEventsHistory.ToListAsync();
            lstPartnerEventsHistory.DataSource = partnerEventsHistory;
        }
    }

    private async void btnLoadPartnerEventMedias_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventMedias = await dbContext.PartnerEventMedias.ToListAsync();
            lstPartnerEventMedias.DataSource = partnerEventMedias;
        }
    }

    private async void btnLoadPartnerEventAttendees_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventAttendees = await dbContext.PartnerEventAttendees.ToListAsync();
            lstPartnerEventAttendees.DataSource = partnerEventAttendees;
        }
    }

    private async void btnLoadPartnerUserSites_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSites = await dbContext.PartnerUserSites.ToListAsync();
            lstPartnerUserSites.DataSource = partnerUserSites;
        }
    }

    private async void btnLoadPartnerSites_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSites = await dbContext.PartnerSites.ToListAsync();
            lstPartnerSites.DataSource = partnerSites;
        }
    }

    private async void btnLoadPartnerRequestEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestEvents = await dbContext.PartnerRequestEvents.ToListAsync();
            lstPartnerRequestEvents.DataSource = partnerRequestEvents;
        }
    }

    private async void btnLoadPartnerSiteConfiguration_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteConfigurations = await dbContext.PartnerSiteConfigurations.ToListAsync();
            lstPartnerSiteConfigurations.DataSource = partnerSiteConfigurations;
        }
    }

    private async void btnLoadPartnerUserEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserEvents = await dbContext.PartnerUserEvents.ToListAsync();
            lstPartnerUserEvents.DataSource = partnerUserEvents;
        }
    }

    private async void btnLoadPartnerEventMessages_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventMessages = await dbContext.PartnerEventMessages.ToListAsync();
            lstPartnerEventMessages.DataSource = partnerEventMessages;
        }
    }

    private async void btnLoadPartnerSitesUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesUsers = await dbContext.PartnerSitesUsers.ToListAsync();
            lstPartnerSitesUsers.DataSource = partnerSitesUsers;
        }
    }

    private async void btnLoadPartnerSiteAdmins_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteAdmins = await dbContext.PartnerSiteAdmins.ToListAsync();
            lstPartnerSiteAdmins.DataSource = partnerSiteAdmins;
        }
    }

    private async void btnLoadPartnerRequestEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestEventsSummary = await dbContext.PartnerRequestEventsSummary.ToListAsync();
            lstPartnerRequestEventsSummary.DataSource = partnerRequestEventsSummary;
        }
    }

    private async void btnLoadPartnerSiteAdminsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteAdminsSummary = await dbContext.PartnerSiteAdminsSummary.ToListAsync();
            lstPartnerSiteAdminsSummary.DataSource = partnerSiteAdminsSummary;
        }
    }

    private async void btnLoadPartnerSiteUsersSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteUsersSummary = await dbContext.PartnerSiteUsersSummary.ToListAsync();
            lstPartnerSiteUsersSummary.DataSource = partnerSiteUsersSummary;
        }
    }

    private async void btnLoadPartnerSitesSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesSummary = await dbContext.PartnerSitesSummary.ToListAsync();
            lstPartnerSitesSummary.DataSource = partnerSitesSummary;
        }
    }

    private async void btnLoadPartnerEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsSummary = await dbContext.PartnerEventsSummary.ToListAsync();
            lstPartnerEventsSummary.DataSource = partnerEventsSummary;
        }
    }

    private async void btnLoadPartnerEventAttendeesSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventAttendeesSummary = await dbContext.PartnerEventAttendeesSummary.ToListAsync();
            lstPartnerEventAttendeesSummary.DataSource = partnerEventAttendeesSummary;
        }
    }

    private async void btnLoadPartnerEventMessagesSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventMessagesSummary = await dbContext.PartnerEventMessagesSummary.ToListAsync();
            lstPartnerEventMessagesSummary.DataSource = partnerEventMessagesSummary;
        }
    }

    private async void btnLoadPartnerEventSummaries_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventSummaries = await dbContext.PartnerEventSummaries.ToListAsync();
            lstPartnerEventSummaries.DataSource = partnerEventSummaries;
        }
    }

    private async void btnLoadPartnerSiteSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteSummary = await dbContext.PartnerSiteSummary.ToListAsync();
            lstPartnerSiteSummary.DataSource = partnerSiteSummary;
        }
    }

    private async void btnLoadPartnerSiteUserSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteUserSummary = await dbContext.PartnerSiteUserSummary.ToListAsync();
            lstPartnerSiteUserSummary.DataSource = partnerSiteUserSummary;
        }
    }

    private async void btnLoadPartnerSiteAdminSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteAdminSummary = await dbContext.PartnerSiteAdminSummary.ToListAsync();
            lstPartnerSiteAdminSummary.DataSource = partnerSiteAdminSummary;
        }
    }

    private async void btnLoadPartnerSiteSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteSummaryView = await dbContext.PartnerSiteSummaryView.ToListAsync();
            lstPartnerSiteSummaryView.DataSource = partnerSiteSummaryView;
        }
    }

    private async void btnLoadPartnerRequestEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestEvents = await dbContext.PartnerRequestEvents.ToListAsync();
            lstPartnerRequestEvents.DataSource = partnerRequestEvents;
        }
    }

    private async void btnLoadPartnerUserEvents_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserEvents = await dbContext.PartnerUserEvents.ToListAsync();
            lstPartnerUserEvents.DataSource = partnerUserEvents;
        }
    }

    private async void btnLoadPartnerRequests_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequests = await dbContext.PartnerRequests.ToListAsync();
            lstPartnerRequests.DataSource = partnerRequests;
        }
    }

    private async void btnLoadPartnerRequestSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestSummary = await dbContext.PartnerRequestSummary.ToListAsync();
            lstPartnerRequestSummary.DataSource = partnerRequestSummary;
        }
    }

    private async void btnLoadPartnerUserEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserEventsSummary = await dbContext.PartnerUserEventsSummary.ToListAsync();
            lstPartnerUserEventsSummary.DataSource = partnerUserEventsSummary;
        }
    }

    private async void btnLoadPartnerUserSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSummary = await dbContext.PartnerUserSummary.ToListAsync();
            lstPartnerUserSummary.DataSource = partnerUserSummary;
        }
    }

    private async void btnLoadPartnerSiteEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteEventsSummary = await dbContext.PartnerSiteEventsSummary.ToListAsync();
            lstPartnerSiteEventsSummary.DataSource = partnerSiteEventsSummary;
        }
    }

    private async void btnLoadPartnerSiteUserEventsSummary_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteUserEventsSummary = await dbContext.PartnerSiteUserEventsSummary.ToListAsync();
            lstPartnerSiteUserEventsSummary.DataSource = partnerSiteUserEventsSummary;
        }
    }

    private async void btnLoadPartnerSites_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSites = await dbContext.PartnerSites.ToListAsync();
            lstPartnerSites.DataSource = partnerSites;
        }
    }

    private async void btnLoadPartnerUsers_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUsers = await dbContext.PartnerUsers.ToListAsync();
            lstPartnerUsers.DataSource = partnerUsers;
        }
    }

    private async void btnLoadPartnerStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerStatus = await dbContext.PartnerStatus.ToListAsync();
            lstPartnerStatus.DataSource = partnerStatus;
        }
    }

    private async void btnLoadPartnerUserEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserEventsSummaryView = await dbContext.PartnerUserEventsSummaryView.ToListAsync();
            lstPartnerUserEventsSummaryView.DataSource = partnerUserEventsSummaryView;
        }
    }

    private async void btnLoadPartnerRequestEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestEventsSummaryView = await dbContext.PartnerRequestEventsSummaryView.ToListAsync();
            lstPartnerRequestEventsSummaryView.DataSource = partnerRequestEventsSummaryView;
        }
    }

    private async void btnLoadPartnerSitesSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesSummaryView = await dbContext.PartnerSitesSummaryView.ToListAsync();
            lstPartnerSitesSummaryView.DataSource = partnerSitesSummaryView;
        }
    }

    private async void btnLoadPartnerSiteUserEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSiteUserEventsSummaryView = await dbContext.PartnerSiteUserEventsSummaryView.ToListAsync();
            lstPartnerSiteUserEventsSummaryView.DataSource = partnerSiteUserEventsSummaryView;
        }
    }

    private async void btnLoadPartnerRequestsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestsSummaryView = await dbContext.PartnerRequestsSummaryView.ToListAsync();
            lstPartnerRequestsSummaryView.DataSource = partnerRequestsSummaryView;
        }
    }

    private async void btnLoadPartnerUserSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSummaryView = await dbContext.PartnerUserSummaryView.ToListAsync();
            lstPartnerUserSummaryView.DataSource = partnerUserSummaryView;
        }
    }

    private async void btnLoadPartnerStatusSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerStatusSummaryView = await dbContext.PartnerStatusSummaryView.ToListAsync();
            lstPartnerStatusSummaryView.DataSource = partnerStatusSummaryView;
        }
    }

    private async void btnLoadPartnerUserSitesSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSitesSummaryView = await dbContext.PartnerUserSitesSummaryView.ToListAsync();
            lstPartnerUserSitesSummaryView.DataSource = partnerUserSitesSummaryView;
        }
    }

    private async void btnLoadPartnerRequestSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestSummaryView = await dbContext.PartnerRequestSummaryView.ToListAsync();
            lstPartnerRequestSummaryView.DataSource = partnerRequestSummaryView;
        }
    }

    private async void btnLoadPartnerSitesSummaryViewBySite_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesSummaryViewBySite = await dbContext.PartnerSitesSummaryViewBySite.ToListAsync();
            lstPartnerSitesSummaryViewBySite.DataSource = partnerSitesSummaryViewBySite;
        }
    }

    private async void btnLoadPartnerUserSummaryViewByUser_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSummaryViewByUser = await dbContext.PartnerUserSummaryViewByUser.ToListAsync();
            lstPartnerUserSummaryViewByUser.DataSource = partnerUserSummaryViewByUser;
        }
    }

    private async void btnLoadPartnerStatusSummaryViewByStatus_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerStatusSummaryViewByStatus = await dbContext.PartnerStatusSummaryViewByStatus.ToListAsync();
            lstPartnerStatusSummaryViewByStatus.DataSource = partnerStatusSummaryViewByStatus;
        }
    }

    private async void btnLoadPartnerRequestSummaryViewByRequest_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestSummaryViewByRequest = await dbContext.PartnerRequestSummaryViewByRequest.ToListAsync();
            lstPartnerRequestSummaryViewByRequest.DataSource = partnerRequestSummaryViewByRequest;
        }
    }

    private async void btnLoadPartnerUserSitesSummaryViewBySite_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSitesSummaryViewBySite = await dbContext.PartnerUserSitesSummaryViewBySite.ToListAsync();
            lstPartnerUserSitesSummaryViewBySite.DataSource = partnerUserSitesSummaryViewBySite;
        }
    }

    private async void btnLoadPartnerSitesUserSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesUserSummaryView = await dbContext.PartnerSitesUserSummaryView.ToListAsync();
            lstPartnerSitesUserSummaryView.DataSource = partnerSitesUserSummaryView;
        }
    }

    private async void btnLoadPartnerRequestsSummaryView_Site_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestsSummaryViewBySite = await dbContext.PartnerRequestsSummaryViewBySite.ToListAsync();
            lstPartnerRequestsSummaryViewBySite.DataSource = partnerRequestsSummaryViewBySite;
        }
    }

    private async void btnLoadPartnerRequestsSummaryView_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestsSummaryViewByUser = await dbContext.PartnerRequestsSummaryViewByUser.ToListAsync();
            lstPartnerRequestsSummaryViewByUser.DataSource = partnerRequestsSummaryViewByUser;
        }
    }

    private async void btnLoadPartnerRequestsSummaryView_Status_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestsSummaryViewByStatus = await dbContext.PartnerRequestsSummaryViewByStatus.ToListAsync();
            lstPartnerRequestsSummaryViewByStatus.DataSource = partnerRequestsSummaryViewByStatus;
        }
    }

    private async void btnLoadPartnerRequestsSummaryView_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestsSummaryViewByDate = await dbContext.PartnerRequestsSummaryViewByDate.ToListAsync();
            lstPartnerRequestsSummaryViewByDate.DataSource = partnerRequestsSummaryViewByDate;
        }
    }

    private async void btnLoadPartnerUserRequestsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserRequestsSummaryView = await dbContext.PartnerUserRequestsSummaryView.ToListAsync();
            lstPartnerUserRequestsSummaryView.DataSource = partnerUserRequestsSummaryView;
        }
    }

    private async void btnLoadPartnerRequestEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestEventsSummaryView = await dbContext.PartnerRequestEventsSummaryView.ToListAsync();
            lstPartnerRequestEventsSummaryView.DataSource = partnerRequestEventsSummaryView;
        }
    }

    private async void btnLoadPartnerUserRequestEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserRequestEventsSummaryView = await dbContext.PartnerUserRequestEventsSummaryView.ToListAsync();
            lstPartnerUserRequestEventsSummaryView.DataSource = partnerUserRequestEventsSummaryView;
        }
    }

    private async void btnLoadPartnerSitesEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesEventsSummaryView = await dbContext.PartnerSitesEventsSummaryView.ToListAsync();
            lstPartnerSitesEventsSummaryView.DataSource = partnerSitesEventsSummaryView;
        }



            private async void btnLoadPartnerSitesUserEvents        }

    private async void btnLoadPartnerSitesUserEventsSummaryViewSitesEventsSummaryView.ToListAsync();
            lstPartnerSitesEventsSummaryView.DataSource = partnerSitesEventsSummaryView;
        }
    }

    private async void btnLoadPartnerSitesUserEventsSummaryView_Click(object sender, EventArgs e)_Click(object sender, EventArgs e)
    {
        using (varSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesUserEvents dbContext = new TrashMobDbContext())
        {
            var partnerSitesUserEventsSummary
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerSitesUserEventsSummaryView = await dbContext.PartnerSitesUserEventsView = await dbContext.PartnerSitesUserEventsSummaryView.ToListAsync();
            lstPartSummaryView = await dbContext.PartnerSitesUserEventsSummaryView.ToListAsync();
            lstPartnerSitesUserEventsSummaryView.DataSource = partnerSitesUserEventsSummaryView;
        }
    }

    private async voidnerSitesUserEventsSummaryView.DataSource = partnerSitesUserEventsSummaryView;
        }
   SummaryView.ToListAsync();
            lstPartnerSitesUserEventsSummaryView.DataSource = partnerSitesUserEventsSummaryView;
        }
    }

    private async void btnLoadPartnerRequest }

    private async void btnLoadPartnerEventsRequestsSummaryView_Click(object sender, btnLoadPartnerEventsRequestsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryView = await dbContext. EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())

            private async void btnLoadPartnerEventsUserRequestsSummaryView_EventsRequestsSummaryView.ToListAsync();
            lstPartnerEventsRequestsSummaryView.DataSource =nerRequestSummaryView.ToListAsync();
            lstPartnerRequestSummaryView.DataSource = partnerRequestSummaryView;
        }
    }

    private async void btnLoadPartnerRequestEventsSummaryView_User_ partnerEventsRequestsSummaryView;
        }
    }

    privateClick(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsUserRequestsSummaryView = await dbContext.PartnerEventsUserRequestsSummary async void btnLoadPartnerEventsRequestsSummaryView_User_Click(object sender, EventArgs e)
    {
        usingClick(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestEventsSummaryViewByUser = await dbContext.PartnerRequestEvents (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestView.ToListAsync();
            lstPartnerEventsUserRequestsSummaryView.DataSource = partnerEventsUserRequestsSummaryView;
        }
    }

    private async void btnLoadPartnerUserEventsSummaryView_Click(object sender, EventArgs esSummaryViewByUser = await dbContext.PartnerEventsRequestsSummaryViewByUser.ToListAsyncSummaryViewByUser.ToListAsync();
            lstPartnerRequestEventsSummaryViewByUser.DataSource = partnerRequestEventsSummaryViewByUser;
        }
    }

    private async void btn();
            lstPartnerEventsRequestsSummaryViewByUser.DataSource = partnerEventsRequests)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserEventsSummaryView = await dbContext.PartnerUserEventsSummaryView.ToListAsync();
            lstPartnerUserEventsSummaryViewByUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryLoadPartnerUserRequestEventsSummaryView_Request_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserRequestView_Status_Click(object sender, EventArgs e)
    {
        using (SummaryView.DataSource = partnerUserEventsSummaryView;
        }
    }

    private async void btnLoadPartnerUserSitesEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobvar dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryEventsSummaryViewByRequest = await dbContext.PartnerUserRequestEventsSummaryViewByRequest.ToListAsync();
            lstPartnerUserRequestEventsSummaryViewByRequest.DataSource = partnerUserRequestEventsSummaryViewByStatus = await dbContext.PartnerEventsRequestsSummaryViewByStatus.ToListDbContext())
        {
            var partnerUserSitesEventsSummaryView = await dbContext.PartnerUserSitesEventsSummaryView.ToListAsync();
            lstPartnerUserSitesEventsAsync();
            lstPartnerEventsRequestsSummaryViewByStatus.DataSource = partnerEventsRequestViewByRequest;
        }
    }

    private async void btnLoadPartnerRequestsSummaryView_Click(object sender, EventArgs e)
    {
        usingsSummaryViewByStatus;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_Date_Click(object sender, EventArgs e) (var dbContext = new TrashMobDbContext())
        {
            var partnerRequestsSummaryView = await db
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByDate = await dbContextContext.PartnerRequestsSummaryView.ToListAsync();
            lstPartnerRequestsSummaryView.DataSource = partnerRequestsSummaryViewByDate;
        }
    }

    private async void btnLoadPartnerUserRequestEventsSummaryView_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserRequestView = await dbContext.PartnerUserRequestEventsSummaryView.ToListAsync();
            lstPartnerUserRequestEventsSummaryView.DataSource = partnerUserRequestView;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_Date_Request_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByDateAndRequest = await dbContext.PartnerEventsRequestsSummaryViewByDateAndRequest.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByDateAndRequest.DataSource = partnerEventsRequestsSummaryViewByDateAndRequest;
        }
    }

    private async void btnLoadPartnerUserSitesEventsSummaryView_Request_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSitesEventsSummaryView = await dbContext.PartnerUserSitesEventsSummaryView.ToListAsync();
            lstPartnerUserSitesEventsSummaryView.DataSource = partnerUserSitesEventsSummaryView;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDate = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDate.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDate.DataSource = partnerEventsRequestsSummaryViewByUserAndDate;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Request_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndRequestAndDate = await dbContext.PartnerEventsRequestsSummaryViewByUserAndRequestAndDate.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndRequestAndDate.DataSource = partnerEventsRequestsSummaryViewByUserAndRequestAndDate;
        }
    }

    private async void btnLoadPartnerUserSitesEventsSummaryView_Request_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSitesEventsSummaryView = await dbContext.PartnerUserSitesEventsSummaryView.ToListAsync();
            lstPartnerUserSitesEventsSummaryView.DataSource = partnerUserSitesEventsSummaryView;
        }
    }

    private async void btnLoadPartnerUserSitesEventsSummaryView_Date_Request_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSitesEventsSummaryView = await dbContext.PartnerUserSitesEventsSummaryView.ToListAsync();
            lstPartnerUserSitesEventsSummaryView.DataSource = partnerUserSitesEventsSummaryView;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_Request_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByRequestAndDate = await dbContext.PartnerEventsRequestsSummaryViewByRequestAndDate.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByRequestAndDate.DataSource = partnerEventsRequestsSummaryViewByRequestAndDate;
        }
    }

    private async void btnLoadPartnerUserSitesEventsSummaryView_Request_User_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerUserSitesEventsSummaryView = await dbContext.PartnerUserSitesEventsSummaryView.ToListAsync();
            lstPartnerUserSitesEventsSummaryView.DataSource = partnerUserSitesEventsSummaryView;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_Date_Request_User_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByDateAndRequestAndUserDate = await dbContext.PartnerEventsRequestsSummaryViewByDateAndRequestAndUserDate.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByDateAndRequestAndUserDate.DataSource = partnerEventsRequestsSummaryViewByDateAndRequestAndUserDate;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_Date_Request_User_Request_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequestDate = await dbContext.PartnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequestDate.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequestDate.DataSource = partnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequestDate;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_Date_Request_User_Request_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequest = await dbContext.PartnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequest.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequest.DataSource = partnerEventsRequestsSummaryViewByDateAndRequestAndUserAndRequest;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDate = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDate.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDate.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDate;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequest = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequest.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequest.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequest;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_User_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_User_User_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUser;
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_User_User_User_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())
        {
            var partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUserAndUser = await dbContext.PartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUserAndAndUserAndUserAndUserAndUserAndUserAndUser.ToListAsync();
            lstPartnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAndUserAndUserAndUserAndUserAndUserAndUserAndUser;UserAndUserAndUserAndUserAndUser.DataSource = partnerEventsRequestsSummaryViewByUserAndDateAndRequestDateAndUserAndRequestAnd
        }
    }

    private async void btnLoadPartnerEventsRequestsSummaryView_User_DateUserAndUserAndUserAndUserAndUserAndUserAndUser;
        }
    }

    private async void btnLoadPart_Request_Date_User_Request_User_User_User_User_User_User_User_User_nerEventsRequestsSummaryView_User_Date_Request_Date_User_Request_User_User_User_User_User_User_Click(object sender, EventArgs e)
    {
        using (var dbContext = new TrashMobDbContext())   
